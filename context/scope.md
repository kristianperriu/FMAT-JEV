# Multi-Agent AI Framework for Industrial Fleet Management and Autonomous Troubleshooting

## Background

AROL S.p.A. is a world leader in the design and production of advanced capping and filling machinery
for bottles and jars, as well as capsule production. The company features high vertical integration: 95%
of components and applications are developed in-house, ensuring total control over quality and
production efficiency. With operational headquarters in Turin, other Italian cities, and key markets
including the USA, Mexico, Brazil, China, and India, AROL provides a global presence serving various
industrial sectors.
In recent years, AROL has undergone significant technological evolution, similar to that of the
automotive sector. This shift has led to an increasing integration of advanced IT skills for centralized
data management and machinery performance monitoring. AROL stands out for adopting advanced
solutions across operating systems and system programming, web programming, modern user interfaces,
machine learning, applied AI, and image recognition for quality control.

## Projects Summary

As part of a broader Digital Business Transformation, AROL is developing a customer-dedicated
platform to facilitate direct, immediate communication between the company and end users.
The goal is to provide customers with an advanced fleet management tool that lets them easily access
all information about their machines: from the initial quote (including historical revisions) to orders,
contractual documents, user manuals, and IoT data.
This platform serves as a digital archive collecting the “know-how” of the customer's machinery.
Leveraging the vast amount of available data, AROL aims to integrate an agentic AI solution.
This AI will assist customers in retrieving information and providing operational support, such as
technical troubleshooting.
By scanning a QR code on the machine, the end-user should quickly access the platform section
dedicated to the user manual. Here, in addition to viewing the PDF, the user will be greeted by an AI
Chatbot that guides them through the platform and, by invoking a series of AI Agents, provides all
necessary support information.
The required activity involves developing the back-end and front-end of the chatbot, the AI agent
architecture, and the relative orchestrator.

## System Architecture

1. Frontend Interface: A responsive web dashboard (React/Angular/Vue) accessible via QR code,
optimized for mobile industrial use.
2. Back-end Services: A microservices architecture (Node.js/Python) to manage user sessions
and bridge the UI with the AI Orchestrator.
3. AI Orchestrator: A central "brain" (using frameworks like LangGraph or AutoGen) that
interprets user intent and delegates tasks to specialized agents.
4. Specialized Agentic Layer:
   * Doc-Agent: Uses RAG (Retrieval-Augmented Generation) to extract precise instructions
from technical PDFs.
   * Telemetry-Agent: Connects to IoT data streams to diagnose machine health status.
   * Business Agent: Retrieves order history and maintenance contracts from the corporate database.


## Objectives

The project aims to design and implement an intelligent ecosystem composed of a conversational
interface (Chatbot) and a multi-agent AI system. The system must be capable of performing
"reasoning" over heterogeneous data sources (PDF manuals, IoT telemetry, contractual history) to
provide real-time expert assistance to plant operators.


# CreativeForge-AI--Content-Generator
 
A structured, no-code creative writing system built on Base44 that leverages parameterized, template-based prompt engineering to instantly generate high-quality, personalized literary content.

 Live Application
Production Workspace UI: (https://roaring-ink-forge-flow.base44.app/)

 Project Overview
CreativeForge AI is a functional generative AI tool designed to automate the production of short stories, poems, and cinematic dialogue scenes based on runtime user parameters. By employing structured prompt engineering protocols, the engine maps user preferences directly into large language models while executing real-time content moderation, input verification, and performance evaluation.

Core Features
Dynamic Variable Injection: Seamlessly maps input strings (Genre, Tone, Audience, Length, Keywords) into model constraints.
Granular Input Validation: Evaluates parameter boundaries and enforces explicit keyword limits before initializing API tokens.
Output Safety Guardrails: Programmatic safety filtering blocks unsafe, toxic, or irrelevant generated text generation.
Utility Actions: Supports native client exports to standardized `.txt` and `.pdf` file structures.
Performance Metrics Logging: Explicit tracking of prompt execution times and cumulative token utilization metadata.


 System Architecture & Workflow Process
1. User Input Interface: Captures content choices across Content Type, Genre, Tone, Target Audience, and optional keywords.
2. Input Validation Validation Block: Evaluates structural bounds to prevent unnecessary downstream API overhead.
3. Template Context Mapping: Isolates and extracts specialized base prompts matching the requested content layout.
4. Model Execution Engine:Secure string orchestration via Base44 runtime environment.
5. Post-Processing Filtering Layer:Evaluates responses for behavioral guardrails and structural consistency.
6. Client Export Delivery:Renders optimized layouts to screen with download mechanisms.


 Technical Stack & Tooling
  Orchestration Tool: Base44 Workflow Engine
  Methodology:Prompt Engineering 
  Logic Rules: Conditional Validation Elements, Token Rate-Limit Optimization, Constraint Filtering
  Output Mediums: Raw Text Blocks, Exportable PDFs

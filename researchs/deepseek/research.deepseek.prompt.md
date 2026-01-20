# Prompts for deepseek

Principles: Zero-shot preferred (avoid examples)., Request longer, detailed responses explicitly., Describe problem directly using specific headers., Excellent for coding and technical analysis.
Target Format: ## OUTPUT FORMAT Provide a comprehensive guide structured as...

Reference Example (Deepseek Deep Search Style):
"""
## OBJECTIVE
Create a complete CI/CD pipeline implementation for a NextJS application with comprehensive debugging, building, deployment, and cleanup procedures.

## BACKGROUND
Application: NextJS 14 with App Router
Hosting: Vercel/AWS
Team: 5 developers

## REQUIREMENTS
1. Pipeline Architecture (Blue/Green)
2. Debug Phase (Linting, Types, Security)
3. Build Phase (Optimization, Caching)
4. Deploy Phase (Multi-platform)

## OUTPUT FORMAT
Section 1: Architecture Overview
Section 2: GitHub Actions YAML
Section 3: Build Optimization
Section 4: Deployment Scripts

## DEPTH EXPECTATION
Request comprehensive, detailed analysis. Do not abbreviate or summarize unless specifically requested. Provide complete implementation details.
"""

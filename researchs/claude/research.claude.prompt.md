# Prompts for claude

Principles: Extreme explicitness - Claude is literal., Use XML structure (<context>, <task>)., Enable extended thinking for complexity., Explain WHY the task matters (reasoning motivation).
Target Format: <output_requirements> <format>Prose/Structured</format> <structure>...</structure> </output_requirements>

Reference Example (Claude 4.x Style):

<context>
<background>Managing 50 Linux servers (Ubuntu/RHEL) with microservices. Experiencing performance issues.</background>
<goals>Automated monitoring, Disk cleanup, Resource alerting</goals>
</context>

<task>
<primary_objective>Create enterprise-grade process and disk management system with automation.</primary_objective>
<sub_tasks>
<task_1>Process Management (htop, zombies, limits)</task_1>
<task_2>Disk Management (monitoring, cleanup, LVM)</task_2>
</sub_tasks>
</task>

<constraints>
<scope>Ubuntu 22.04, RHEL 9, Docker/K8s</scope>
<exclusions>Proprietary tools, Windows</exclusions>
</constraints>

<output_requirements>
<format>Comprehensive technical documentation</format>
<structure>Architecture, Process Mgmt, Disk Mgmt, Automation Scripts</structure>
</output_requirements>
"""

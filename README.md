# LiveSmart Integrations & Custom Skills

Practical integration notes and custom skills for combining the forked tools with OpenMontage to expand LiveSmart capabilities (video production, automation, research, planning, design, Microsoft tools, communication).

## Core Video/Agentic Stack

### OpenMontage + Pixelle-Video
- Use OpenMontage for complex, multi-stage productions (research, scripting, asset generation, editing).
- Use Pixelle-Video for high-volume short-form content (fast topic-to-video pipeline).
- Integration idea: Generate quick shorts in Pixelle-Video, then bring strong assets or clips into OpenMontage for more advanced editing and faith/family-focused storytelling.

### OpenMontage + ViMax
- ViMax excels at multi-agent consistency (Director + Screenwriter + Producer).
- Good for narrative or series content where character/scene consistency matters (e.g., client transformation stories over multiple videos).
- Combine with OpenMontage's production pipelines for higher-end or longer-form work.

### OpenMontage + video-use / claude-code-video-toolkit
- These are excellent for agent-driven video editing and post-production.
- Use them to extend OpenMontage's editing capabilities or for fast agent-based refinements.

## Automation Layer

### n8n + browser-use + langgraph
- n8n for workflow orchestration and automation across tools.
- browser-use for agent-driven research and execution.
- langgraph for stateful multi-agent planning and complex pipelines.
- Integration: Build automated research → content planning → video production pipelines that feed into OpenMontage or Pixelle-Video.

## Research & Learning

### langchain + transformers + huggingface
- Strong foundation for research agents, knowledge retrieval, and model integration.
- Use for deep topic research before video production or for building custom LiveSmart knowledge bases.

## Planning & Business

### vercel + github/roadmap + langgraph
- vercel for deployment and optimization of any web tools or landing pages.
- github/roadmap for visibility into planning.
- langgraph for advanced planning agents.
- Build business/operational automation on top of the video tools.

## Graphic Design

### tailwindcss + chakra-ui
- Modern design systems for consistent branding across content, websites, and client materials.
- Integrate with Canva for final polish and video export.

## Microsoft / Communication / Optimization

### Microsoft-Teams-Samples + bolt-js + msgraph-sdk
- Microsoft tools for internal communication and automation.
- bolt-js for Slack integration and team workflows.
- Use for client communication, team coordination, or business process automation around content production.

## Recommended Multi-Angle Production Approach

1. **High-volume shorts** — Pixelle-Video + n8n automation
2. **Narrative / series content** — ViMax + OpenMontage
3. **Complex / high-production** — OpenMontage as central orchestrator + video-use for editing
4. **Research & Planning** — langchain/langgraph + browser-use
5. **Design & Branding** — tailwindcss/chakra-ui + Canva
6. **Business & Microsoft integration** — Microsoft Graph + Teams + automation tools

## Next
Custom LiveSmart Director Skills and specific integration scripts will be added here.
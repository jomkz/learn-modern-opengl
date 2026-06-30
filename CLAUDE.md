# CLAUDE.md — Modern OpenGL Learning Path

This file orients Claude Code to the repo structure and conventions so each session starts with full context.

## What this repo is

A structured 6-phase learning path covering modern OpenGL graphics programming, from the rendering pipeline through advanced lighting techniques. Documentation only — code exercises reference LearnOpenGL.com.

## Repo structure

```
README.md   — full curriculum (all phases, concepts, resources)
LICENSE     — MIT
```

## Conventions

- All curriculum lives in `README.md` — there is no separate docs directory
- Phases progress linearly: each builds on the previous
- Primary external resource: https://learnopengl.com
- Dependencies noted per phase: GLFW/SDL2, GLAD/GLEW, GLM, Assimp

## Adding content

- Add new sections to `README.md` following the existing phase format
- Each phase has: objectives, key concepts, recommended resources, and a project
- Reference LearnOpenGL.com chapters where applicable

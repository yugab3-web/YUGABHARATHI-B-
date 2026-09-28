# Phase 3 – Project Design

## Architecture

User
  ↓
Streamlit UI
  ↓
Input validation
  ↓
Prompt Engineering
  ↓
Gemini API
  ↓
Generated 7-Day Routine
  ↓
Streamlit Display

## Main components
- UI component: Streamlit
- Logic component: Python
- AI component: Gemini
- Output component: Streamlit markdown display

## Data flow
1. User enters preferences.
2. Python reads the values.
3. Python creates a structured prompt.
4. Gemini processes the prompt.
5. Response is returned.
6. The app displays the result.

task:
  name: Generate Video Prompts
  description: Convert a script into AI video generation prompts.
  input:
    - script_segment
    - visual_style
    - character_refs
  output:
    - prompt_list
  steps:
    - Break script into shots (3-5s each).
    - For each shot, define Subject, Action, Environment, Lighting, Camera.
    - Apply consistent character tags.
    - Format for specific AI model (Vidu/Sora).

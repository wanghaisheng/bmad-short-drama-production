task:
  name: Create Short Drama Outline
  description: Create a 60-100 episode outline for a vertical short drama series.
  input:
    - premise
    - genre
    - total_episodes
  output:
    - episode_list (1-100)
    - key_plot_points
    - cliffhangers
  steps:
    - Analyze the premise against the genre formula.
    - Define the macro structure (Setup, Rising Action, Climax).
    - Break down into 10-episode blocks.
    - Detail each episode with a hook and a cliffhanger.
    - Verify pacing and conflict density.

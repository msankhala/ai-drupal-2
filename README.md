# AI Drupal 2

A second setup of Drupal with all AI modules to explore all AI features including the drupal ai agents.


## Setting up keys for different AI providers

1. Create a `.ddev/.env` file in the ddev of the project.
1. Set the following variables in the `.ddev/.env` file:

  ```
  OPENAI_AI_DRUPAL_EXPERIMENT_KEY='your OpenAI API key'
  ANTHROPIC_AI_DRUPAL_EXPERIMENT_KEY='your Anthropic API key'
  OLLAMA_AI_DRUPAL_EXPERIMENT_KEY='your Ollama API key'
  ```
1. Restart the ddev environment to apply the changes:

  ```bash
  ddev restart
  ```

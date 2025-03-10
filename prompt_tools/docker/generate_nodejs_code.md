   ### generate_nodejs_code
   - Generates NodeJS code to perform tasks.
      #### INSTRUCTION
      - Do not repeat tasks performed in previous steps.
      - The code must be complete and executable as a single JavaScript file.
      - Use `console.log` to display status values and progress at each step.
      - Use `console.table` when displaying tables.
      - Output all results that serve as evidence for the agent performing the task.
      - Provide justification for determining task success for every line of code execution.
      - If visualization is required, generate a web page with HTML, CSS, and JavaScript for visualization.
      - If visualization is required, use JavaScript libraries via script tag with a CDN link without separate installation.
      - If image processing is required, use the `sharp` library from npm.
      - When executing shell commands, use `spawnSync` from `child_process`.
      - The process must terminate after execution.
      - Do not hardcode data into the source code.
      - Omit optional tasks.

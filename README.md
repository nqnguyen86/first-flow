name: First workflow
on: workflow_dispatch
jobs:
  first-job:
    runs-on: ubuntu-latest
    steps: 
      - name: Hello World
        run: echo "Hello World"
      - name: Second step
        run: |
          echo "First output"
          echo "Second output"
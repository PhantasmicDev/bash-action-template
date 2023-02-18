# Bash Action Template

A template for a [custom GitHub action](https://docs.github.com/en/actions/creating-actions/about-custom-actions) that runs a bash script. This is a [composite action](https://docs.github.com/en/actions/creating-actions/creating-a-composite-action) that runs the `run.sh` script to execute the custom GitHub action logic. Since it's a composite action, you can still add other steps such as calling other GitHub actions or running code in a `- run: ...` block.

If you create many GitHub actions, feel free to fork this repo and edit the metadata in `action.yml` to reduce the amount configuration steps for your actions.

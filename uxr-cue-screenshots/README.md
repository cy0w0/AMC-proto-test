Put UXR cue screenshots in this folder and list them in manifest.json.

Example manifest entry:

[
  {
    "id": "manual-entrypoint-1",
    "src": "uxr-cue-screenshots/manual-entrypoint-1.png",
    "flows": ["manual"],
    "steps": ["entrypoint"],
    "questionTexts": {
      "entrypoint": [
        "What do you think this entrypoint is offering?"
      ]
    }
  }
]

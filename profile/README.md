Join us at V-Sekai, an open-source VR community dedicated to creating a user-friendly and free virtual reality platform. Connect with us on our [Discord server](https://discord.gg/7BQDHesck8)! 

`vī-sekai` translates to "V-World" in English.

## Get Involved

1. **Chat**: Connect with us on [Discord](https://discord.gg/7BQDHesck8).
2. **Test**: Try out our latest builds [here](https://v-sekai.github.io/manuals/features/play_latest.html).

```mermaid
graph TD
    A[Start] --> B{Are you a creator?}
    B -->|Yes| C[Upload Avatars]
    C --> D[Upload Worlds]
    D --> E[Work on V-Sekai]
    E --> F{Want to get involved?}
    B -->|No| Y[End]
    subgraph Involvement Path
    F -->|Yes| G(Join Discord)
    G --> H[Test Latest Builds]
    H --> I[Submit Feedback]
    I --> J{Want to play the latest build?}
    J -->|Yes| K[Visit CI Server]
    K --> L[Download Artifacts]
    L --> M[Play Latest Build]
    J -->|No| Y[End]
    end
    F -->|No| Y[End]
```
# Contributing to the Project
## Adding Features
Requests for changes and new features should be added to Issues for the team to review and develop the ideas.
Once a decision is reached, the result of the conversation should appear in the Wiki in detailed format.
Specifically, the contents of the Wiki should contain solely technical information.
It is not to have references to team member names, conversations, or first-person perspective, only an objective viewpoint and the technicals of the new feature or change.

The Wiki will have the following heirarchy:
- Specification
  - Current
    - Components
      - Renderer
        - Features
          - Hardware Acceleration
        - Deprecated
          - Triple Buffering
      - Deprecated
        - Texture Mapper
  - Release
    - v0.1
      - Components
        ...
    - v0.2
      ...
    - vx.x
Features that are abandoned, removed, or overhauled are not to be erased from the Wiki, simply versioned away or moved to a dedicated Deprecated section.

Changes that happen to a spec before it is assigned a version number do not need to be preserved.
For instance, if the design for the Renderer were to change after the original spec is assigned v0.1,
and then was to change again before a new number is assigned to the spec, it is safe to override the document contents under Current.

Once a spec is declared finalized, the spec is to be fully reviewed and assigned a version number.  
The Wiki will then be updated, with all final specification details for that version to appear under its assigned version number in the Release section.

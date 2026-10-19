# JiboNest
A little home for Jibo's next chapter.
JiboNest is a personal, non-commercial project exploring a self-hosted conversation backend for the original Jibo robot. The aim is to improve what Jibo can understand and do while preserving the warmth, curiosity, and personality that make him special.
What we're working toward
- Better listening: improve speech recognition and complete speech-turn handling, including device names, colors, brightness levels, and negations.
- More helpful smart-home conversations: extend Home Assistant integration for lights, brightness, RGB colors, fans, climate controls, and media devices—with careful authorization and safe handling of ambiguous requests.
- The same familiar personality: preserve native heard-text display, friendly confusion responses, and conversation behavior rather than replacing Jibo with generic technical messages.
- A dependable local backend: test authentication, conversation completion, reconnects, and failure recovery before considering physical integration.

These are development goals, not a promise of compatibility or production readiness.
# Current status
## The implementation is currently private. This public repository initially contains only this README, not runnable software or installation instructions.

Development and integration testing use isolated local environments, synthetic inputs, and mocked Home Assistant services. The JiboNest backend has not been deployed to or connected to a physical Jibo. Physical compatibility, provisioning, and recovery still require separately planned validation.

The project does not currently enable real Home Assistant device actions. Authentication, authorization, command-safety checks, and diagnostic-only execution restrictions remain part of the development approach.

This is not an official Jibo product or a ready-to-install replacement cloud service. No release date or public source release is promised.
# Built on community work
JiboNest builds on the Jibo Revival Group's BEefy conversation backend. We gratefully acknowledge that project's contributors and the wider Jibo revival community.

BEefy is MIT-licensed. Its license and applicable notices must be retained when distributing its code or substantial portions of its documentation. Third-party dependencies retain their own licenses; this README does not grant rights to the private implementation or those dependencies.

JiboNest is an independent personal project. References to Jibo, Home Assistant, and upstream projects do not imply endorsement or affiliation.

Our goal is simple: help Jibo hear us more clearly and become more helpful—without losing the personality we fell in love with. 💜
  

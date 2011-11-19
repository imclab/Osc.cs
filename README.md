# Extremely minimal OSC implementation.

- OSC packet parser (for reception)
  - converts packet to object[]
- OSC packet builder (for sending)
  - provides simple variadic API
- Only basic types ('i', 'f', 's') without blobs.
- No bundles.
- No transport layer (send and receive yourself, however you please).
  - example of UDP transport:
    [SCClient.cs](https://github.com/artm/Cyrus/blob/master/Assets/Standard%20Assets/SCClient.cs)
- No comments (read the fucking code)

## Rationale

My goal was to receive sound spectrum from SuperCollider in Unity. My goal is
achieved.

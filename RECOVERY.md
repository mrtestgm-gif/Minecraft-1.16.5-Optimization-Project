# Verified optimized-client recovery

The HTML was recovered by replaying the recorded patches without changing their
implementation. It is byte-for-byte identical to the previously verified result:

- File: `eaglercraft-1.16.5-optimized.html`
- Size: 46,881,130 bytes
- SHA-256: `e3e0d7400fade55afe792b393e090ebfb18521aec0066af283a28799e634f714`

`eaglercraft-1.16.5-optimized.zip` contains that exact HTML. This ZIP is newly
packaged; the HTML inside is the unchanged verified client. `SHA256SUMS.txt`
records the hashes of both files. `.gitattributes` prevents newline conversion
of these payloads on checkout.

This recovery does not introduce new optimizations or new test claims. Existing
Clever branding, loading screens/icon, server configuration and early beforeunload
code remain part of the hash-identical HTML. The previously documented limitations,
including original-client player-position reset and unverified Chromebook/file
launch/multiplayer coverage, are not newly fixed by this recovery.

For a private repository, sign into an authorized GitHub account before downloading.
Open the HTML or ZIP file on this branch and use GitHub's Download raw file button.

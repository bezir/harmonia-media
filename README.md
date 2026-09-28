# harmonia-media

Public lesson media for the Harmonia beta. All files here are generated:
Seedance video clips + kokoro TTS narration, assembled with ffmpeg.
Verify downloads against these hashes:

| lesson | duration | bytes | sha256 |
|---|---|---|---|
| hist-l1 | 87.0s | 18196794 | `a8157d71fa126af901716f2eeb9dcda02ac968e1c48840e3d959c8ac3d1bc236` |
| hist-l5 | 80.72s | 18712217 | `8a01a83508673b36ab388fa2c81230b84a678e0f4dc6e33eebeabe2c5e7eb2af` |
| hist-l3 | 98.2s | 16959394 | `445ff71d9913c67588fe74dd2fc8f32ffe706365151ade6b17d4fdd2ae76de10` |
| gk-l2 | 64.5s | 15352703 | `28a83900da78fa2e1f60541a980656a80e60d45ed3534eb7c0cdef8687084320` |
| gk-l4 | 82.03s | 18847163 | `7cbec4f452344fbdd67c7817f71f2af26754d2fa3d2e18349b8425f16a958139` |
| psy-l1 | 81.38s | 16217050 | `db1a6d716c33d2a73fd8c1f6c4c1dfcc0295aa1d6df53c0c9337538050c7b7bc` |
| psy-l2 | 81.15s | 17697450 | `ee51361ede2be14ab14270435df2fde69d157df4f62de866afc9bd88d9b16a48` |
| psy-l4 | 87.1s | 16834926 | `24c60ded6e01041141e0602b90f0a2a72c42f6e6428b2efdc47dc798ccc6dcb3` |

Source release: `lesson-media-v1` (immutable; never re-upload under this tag).

Canonical playback URLs (CORS-clean, pinned to the binaries commit):

```
https://raw.githubusercontent.com/bezir/harmonia-media/675e906abfc1b16df2c79765ab214ce0945c7040/<lesson>.mp4
```

The `lesson-media-v1` release keeps identical bytes as a backup; prefer
the raw URLs above (release downloads lack CORS headers for web video).

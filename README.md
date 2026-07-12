# Djordje Andjelkovic

**Senior Software Engineer — C++ · Real-time Visualization · On-device ML**
Belgrade, Serbia · [LinkedIn](https://www.linkedin.com/in/djordje-andjelkovic-9b20a9193/) · andjelkovicdjordje@hotmail.com

I build systems that cross layers: microsecond-latency C++ trading infrastructure on one
end, GPU particle visualization (CesiumJS / GLSL) and in-browser ML inference (Whisper on
ONNX Runtime Web, WebGPU/WASM) on the other.

Most of my work lives in private repos — an HFT crypto exchange and a real-time geospatial
situational-awareness platform. Here's what's public:

## Upstream open source — MindsDB (~40k★)

Hit real limitations of MindsDB's Ray Serve integration while running it in production,
and fixed them upstream — **4 merged PRs**:

- [#10371 — RayServeHandler propagates predict params](https://github.com/mindsdb/mindshub/pull/10371)
- [#10462 — Pass params in Ray Serve create](https://github.com/mindsdb/mindshub/pull/10462)
- [#10449 — Parquet data marshalling](https://github.com/mindsdb/mindshub/pull/10449)
- [#10553 — JSON error propagation when Parquet fails](https://github.com/mindsdb/mindshub/pull/10553)

## Currently

On-device speech-to-text and voice-command routing in the browser, GPU wind & ocean-current
visualization, and the reactive Svelte architecture that ties it together.

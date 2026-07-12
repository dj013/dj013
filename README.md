# Djordje Andjelkovic

**Senior Software Engineer - C++ · Real-time Visualization · ML Systems**
Belgrade, Serbia · [LinkedIn](https://www.linkedin.com/in/djordje-andjelkovic-9b20a9193/) · andjelkovicdjordje@hotmail.com

I build systems that cross layers: microsecond-latency C++ trading infrastructure on one
end, GPU particle visualization (CesiumJS / GLSL) and in-browser ML inference (Whisper on
ONNX Runtime Web, WebGPU/WASM) on the other.

My main production work lives in private repositories, spanning an HFT crypto exchange
and a real-time geospatial situational-awareness platform.

## What I work on

- **C++ systems** - low-latency services on an in-house actor framework, Aeron/SBE
  messaging, typed database libraries, Bazel monorepo toolchains
- **ML systems** - time-series anomaly detection, MLflow, Ray Serve, FastAPI,
  Parquet data paths, QuestDB ingestion
- **On-device AI** - Whisper STT, ONNX Runtime Web, transformers.js, WebGPU/WASM,
  quantized inference (fp32/fp16/q4)
- **Graphics & geospatial** - CesiumJS, GLSL particle systems, weather, ocean-current
  and satellite visualization

## Upstream open source - MindsDB (~40k★)

Hit real limitations of MindsDB's Ray Serve integration while running it in production,
and fixed them upstream. **4 merged PRs:**

- [Propagate prediction parameters through RayServeHandler (#10371)](https://github.com/mindsdb/mindshub/pull/10371)
- [Pass training parameters during Ray Serve model creation (#10462)](https://github.com/mindsdb/mindshub/pull/10462)
- [Parquet-based dataframe marshalling (#10449)](https://github.com/mindsdb/mindshub/pull/10449)
- [Preserve JSON error responses when Parquet handling fails (#10553)](https://github.com/mindsdb/mindshub/pull/10553)

## Currently

Building browser-native speech recognition and voice-command routing, GPU wind and
ocean-current visualization, and the reactive Svelte architecture that ties them together.

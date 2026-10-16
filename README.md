# Djordje Andjelkovic

**Senior Software Engineer - C++ · Real-time Visualization · ML Systems**
Belgrade, Serbia · [LinkedIn](https://www.linkedin.com/in/djordje-andjelkovic-9b20a9193/) · andjelkovicdjordje@hotmail.com

Senior Software Engineer with 4+ years at Inceptive, working across C++ systems, real-time
geospatial visualization and applied ML. Most of that work lives in private repositories:
an HFT crypto exchange and a real-time 3D globe platform for situational awareness.

## What I work on

- **C++ systems** - services on an in-house actor framework (Aeron/SBE messaging),
  ScyllaDB and QuestDB client libraries, TCP reconnect reliability, Bazel monorepo toolchains
- **LLM agents** - an in-app agent that operates a 3D globe through validated tools,
  sandboxed code execution (OpenCode), hand-off between agents over MCP
- **ML systems** - time-series anomaly detection, MLflow, Ray Serve, FastAPI,
  Parquet data paths, QuestDB ingestion
- **In-browser ML** - Whisper speech recognition on ONNX Runtime Web (WebGPU/WASM)
- **Graphics & geospatial** - CesiumJS, GLSL particle systems for wind and ocean currents,
  satellite tracking, live data layers

## Upstream open source - MindsDB (~40k★)

Hit real limitations of MindsDB's Ray Serve integration while running it in production,
and fixed them upstream. **4 merged PRs:**

- [Propagate prediction parameters through RayServeHandler (#10371)](https://github.com/mindsdb/mindshub/pull/10371)
- [Pass training parameters during Ray Serve model creation (#10462)](https://github.com/mindsdb/mindshub/pull/10462)
- [Parquet-based dataframe marshalling (#10449)](https://github.com/mindsdb/mindshub/pull/10449)
- [Preserve JSON error responses when Parquet handling fails (#10553)](https://github.com/mindsdb/mindshub/pull/10553)

## Currently

Working on the globe platform's LLM agent, shared live rooms where several people see the
same map, and the C++ networking and storage fixes underneath them.

# Hi, I'm Wajahat Ahmed

AI Engineer at [Lambda Theta](https://github.com/Lambdatheta), ELM Research Team, Karachi. I design and ship production AI systems — retrieval-augmented generation, LLM agents, and multi-camera computer vision — and I'm doing an MS in Artificial Intelligence at NED University alongside the job.

Before this I spent two years as a Research Assistant at the Neurocomputation Lab (NCAI–NED), building AIoT systems, embedded firmware, and vision pipelines; one of those systems became a peer-reviewed paper.

[Portfolio](https://wajahatah.github.io) · [LinkedIn](https://www.linkedin.com/in/wajahat-ahmed-hashmi) · [Google Scholar](https://scholar.google.com/citations?user=tLXgrq0AAAAJ) · [ORCID](https://orcid.org/0009-0008-9215-9807)

## What I work on

- **Retrieval and document intelligence** — modular RAG platforms end to end: ingestion, OCR, chunking, hybrid retrieval (dense + BM25 with reciprocal rank fusion), cross-encoder reranking, and grounded answers with citations.
- **Agentic systems** — event-driven assistants and multi-step LLM workflows over chat platforms and enterprise data.
- **Computer vision in production** — pose-keypoint behaviour detection, action recognition, and video analytics across 20+ concurrent RTSP streams.

## Featured projects

| Project | What it is | Stack |
| --- | --- | --- |
| [ragkit](https://github.com/wajahatah/ragkit) | RAG platform built as a modular monolith: four services that run as one process or four containers by configuration. Hybrid retrieval, cross-encoder reranking, cited answers, and built-in evaluation. | Python · FastAPI · Docker Compose · CI |
| [docling-custom-ocr](https://github.com/wajahatah/docling-custom-ocr) | Plugs a custom HTTP OCR backend into Docling without forking it, wrapped as a FastAPI chunking service with multiple chunking strategies. | Python · Docling · FastAPI · Docker |
| [Conversational_Task_Assistant](https://github.com/wajahatah/Conversational_Task_Assistant) | Progress-aware task assistant for Telegram and Discord: natural-language task entry, risk-aware nudges as deadlines approach, daily briefings, and pluggable LLM backends (Ollama, Hugging Face, OpenAI, Gemini, Claude). | Python · Docker · LLM APIs |
| [keypoint-behaviour-detection](https://github.com/wajahatah/keypoint-behaviour-detection) | Hand-raise, looking-around, hand-in-pocket, and action detection from YOLO-Pose keypoints, plus the dataset tooling behind it (COCO→YOLO, annotation reshaping, Keras→ONNX). | PyTorch · YOLO-Pose · OpenCV |
| [VisionInk](https://github.com/wajahatah/VisionInk) | Draw in the air: real-time MediaPipe hand-landmark drawing with gesture-controlled colour, brush size, undo, and clear. | Python · MediaPipe · OpenCV |
| [translation_extension](https://github.com/wajahatah/translation_extension) | Chrome extension that translates selected Arabic text inline — Quran-aware with verse references, OCR for images, and a built-in PDF viewer. | JavaScript · Tesseract / EasyOCR |

## Work I can't open-source

Most of my recent work is private — enterprise and lab code I don't have the right to publish. At the architecture level:

- **Document-intelligence / RAG-as-a-service platform** — modular AI microservices (FastAPI, PostgreSQL, Redis, Milvus) covering ingestion, embedding generation, vector indexing, and semantic search; containerised with CI/CD across local GPU infrastructure and Google Cloud.
- **Multi-camera human activity recognition** — hybrid spatial-temporal deep learning over 20+ concurrent RTSP streams, trained on 200K+ labelled samples and 1,200+ video sequences; robust to viewpoint change, occlusion, and concurrent actions.
- **Public-safety and remote-sensing CV** — drink-spiking detection on public CCTV; satellite-imagery scene understanding and vehicle detection.
- **AIoT research systems (Neurocomputation Lab)** — SmartFan, a retrofittable ESP32/BLE ceiling-fan controller with ML fan-speed prediction (published); InstruX, industrial energy-analyzer monitoring over RS-485 and MQTT (paper under review); RoboDoc, a vitals-monitoring assistive robot (runner-up, Engineering Excellence Award); Li-ion battery characterisation rigs.

Photos and write-ups for all of these are on my [portfolio](https://wajahatah.github.io/project.html).

## Publications

- **Design and Experimental Results of an AIoT-Enabled, Energy-Efficient Ceiling Fan System.** *Sustainability* 16(12), 5047, 2024. [doi:10.3390/su16125047](https://doi.org/10.3390/su16125047)
- *Dataset of the Energy and Power Consumption of a Higher Educational Institute.* Under review, *Scientific Data*.

## Background

- MS Artificial Intelligence, NED University — in progress (2026–)
- BS Applied Physics (Electronics), NED University — Gold Medalist, 2022
- Google Cloud Associate Cloud Engineer, 2026
- I supervise undergraduate research projects at the Neurocomputation Lab

Reach me at wajahat.ahmedhashmi@gmail.com.

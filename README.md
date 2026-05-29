# Unity CAD Conversion Pipeline

A scalable CAD/BIM asset conversion pipeline built with Unity for transforming industrial design files into optimized 3D assets and structured TypeScript metadata.

## Overview

This project provides an end-to-end pipeline for processing CAD and BIM files such as:

* DWG
* Revit
* IFC
* STEP
* FBX
* GLB

The system uses Unity as the core processing engine to automate:

1. CAD/BIM import
2. Scene hierarchy cleanup
3. Mesh optimization
4. Metadata extraction
5. GLB export
6. TypeScript data generation

The generated output can be integrated into:

* Digital Twin platforms
* Web-based 3D viewers
* Facility management systems
* Industrial visualization dashboards
* IoT and smart building systems

---

# Features

* Unity-based CAD processing workflow
* Automated hierarchy cleanup
* Mesh decimation and optimization
* Metadata extraction pipeline
* GLB export support
* TypeScript model generation
* Headless Unity batch processing
* Digital Twin ready architecture

---

# Pipeline Flow

```text
CAD / BIM Files
        ↓
Unity Import Pipeline
        ↓
Hierarchy Cleanup
        ↓
Mesh Optimization
        ↓
Metadata Extraction
        ↓
GLB Export
        ↓
TypeScript Generation
```

---

# Technologies

* Unity
* TypeScript
* GLTF / GLB
* CAD Import Tools
* Unity Asset Transformer
* Headless Unity Batchmode

---

# Example Use Cases

* Smart Factory Visualization
* Building Information Modeling (BIM)
* Industrial Digital Twin
* Facility Monitoring Systems
* Real-time 3D Asset Streaming

---

# Repository Structure

```text
Assets/
Scripts/
Pipeline/
Export/
Generated/
Metadata/
```

---

# Running the Pipeline

## Unity Headless Mode

```bash
Unity.exe -batchmode -quit -projectPath . -executeMethod Pipeline.Run
```

---

# Output Example

## GLB Assets

```text
/output/models/
```

## Generated TypeScript

```typescript
export interface AssetMetadata {
  id: string;
  name: string;
  category: string;
  position: Vector3;
}
```

---

# Future Improvements

* Automated cloud processing
* Web API integration
* IFC semantic extraction
* Real-time synchronization
* AI-assisted asset classification

---

# License

MIT License

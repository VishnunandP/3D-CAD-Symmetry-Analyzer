# 3D-CAD-Symmetry-Analyzer

A precision geometry processing tool that detects and annotates dominant symmetry planes in 3D CAD models using OpenCascade and PythonOCC. Outputs are exported as enriched STEP files for use in downstream CAD/CAM workflows, quality control, and manufacturing inspection.

Key Features

- Symmetry Plane Detection: Automatically detects reflectional symmetries in 3D shapes via geometric heuristics.
- Native TopoDS_Shape Integration: Analyzes raw BREP-based shapes and overlays symmetry annotations.
- Robust STEP Exporting: Resolves OpenCascade export exceptions for reliable STEP file generation with persistent metadata.
- Real-Time 3D Rendering: Runs interactively in Jupyter or Google Colab with real-time shape visualization and overlays.
- Industry Use-Case Ready: Designed for use in CAD/CAM pipelines, part verification, and automated geometric reasoning tasks.

Technologies Used

- PythonOCC / OpenCascade: CAD kernel for shape analysis and STEP export
- STEPControl, TopoDS_Shape, gp_Pln: Core geometry and export classes
- NumPy: Vector algebra and plane fitting
- Jupyter / Google Colab: Development and real-time visualization

Installation and Usage

1. Clone the repository:
   git clone https://github.com/VishnunandP/CAD-Symmetry-Plane-Exporter.git
   cd CAD-Symmetry-Plane-Exporter

2. Set up environment:
   Install dependencies (Python 3.8+):
   pip install -r requirements.txt

3. Run in Jupyter:
   jupyter notebook
   Or open directly in Google Colab

4. Load your .STEP file and run symmetry_analysis.ipynb

Sample Output

- Annotated 3D geometry with overlayed symmetry planes
- Exported .step file with geometric metadata preserved
- Diagnostic logs for shape and plane fitting confidence

Applications

- CAD Model Validation
- Manufacturing Inspection
- Reverse Engineering
- CAM Path Planning
- Educational Geometry Tooling

License

MIT License © 2025 Vishnunand Pillai

Links

- GitHub: https://github.com/VishnunandP/CAD-Symmetry-Plane-Exporter
- OpenCascade Documentation: https://dev.opencascade.org/doc/overview/html/index.html

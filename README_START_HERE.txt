TYRETRACK V4.8.2 - COMPLETE CLEAN GITHUB REPOSITORY

1. On GitHub, create a NEW EMPTY repository, for example TyreTrack-V4-8-2-Clean.
2. Extract this ZIP on your computer. Do not upload the ZIP itself.
3. Upload ALL files in the extracted folder to the repository root.
   IMPORTANT: GitHub browser folder upload may not preserve the hidden .github folder.
4. If the .github/workflows/build-windows.yml file is not uploaded correctly:
   use Add file > Create new file, enter .github/workflows/build-windows.yml,
   paste the contents of the extracted file, and commit.
5. Check Code tab for TyreTrack.spec, requirements-build.txt, tyre_detector.pt,
   tracking_smoke_test.py, and .github/workflows/build-windows.yml.
6. Open Actions > Build TyreTrack Windows - SciPy Fixed > Run workflow.
7. Download the artifact from the successful run and Extract All.
8. Run TyreTrack.exe inside its extracted folder.

This is the existing V4.8.2 CPU-only app with a packaging fix and a new
--self-test-tracking option. It is NOT the planned V5 dual-camera CUDA build.
The GitHub workflow tests real YOLO tracking in the packaged EXE before
publishing an artifact. Actual conveyor counting still requires field tests.

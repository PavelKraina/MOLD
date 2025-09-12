MOLD – Modular Layout Designer

MOLD (Modular Layout Designer) is an open-source KNIME application for
designing experimental plate layouts compatible with Echo acoustic
liquid handlers.
It helps researchers easily create custom layouts for dose-response
experiments, screening assays, and dilution series without programming
skills.

------------------------------------------------------------------------

✨ Features

-   Import compound information from multiple source plates (.csv)
-   Generate dose-response concentration series with customizable
    dilution factors
-   Automatic calculation of transfer volumes adjusted to Echo droplet
    size (2.5 or 25 nL)
-   Backfill solvent normalization (DMSO or H₂O) with user-defined
    volumes
-   Support for 96-, 384-, and 1536-well plate formats
-   Flexible replicate arrangements (side-by-side or block layout)
-   Export instruction files for Echo Plate Reformat and Echo Cherry
    Pick software
-   Integrated Plate Heatmap Viewer for visual QC of concentrations,
    volumes, and plate layouts
-   Stores and reloads last-used settings for reproducibility

------------------------------------------------------------------------

🚀 Installation & Usage

1.  Download the provided MOLD.knar file from this repository.
2.  Open it in KNIME.
3.  When prompted, install all missing KNIME extensions/packages.
4.  Load your input file(s) via the File Importer node and follow the
    graphical interface.

Example input file: input_example.csv (included in the repository).

------------------------------------------------------------------------

📖 Documentation

Detailed instructions and use cases are available in the MOLD
Documentation (dose-response layout, double-concentration screen, etc.).
Additional changelogs can be found in the changelog folder.

------------------------------------------------------------------------

📸 Example

(You can insert here a screenshot of the KNIME workflow or heatmap
viewer)

------------------------------------------------------------------------

📜 License

This project is released under the MIT License. See LICENSE for details.

------------------------------------------------------------------------

👥 Authors

Developed by:
- Pavel Kraina, Institute of Organic Chemistry and Biochemistry, Czech
Academy of Sciences
- Matúš Drexler, Institute of Organic Chemistry and Biochemistry, Czech
Academy of Sciences

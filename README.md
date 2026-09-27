        # WIDER FACE

        [![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-green?logo=creativecommons&logoColor=white)](https://creativecommons.org/licenses/by/4.0/)
        [![GitHub](https://img.shields.io/badge/GitHub-biometric--community%2FWIDER--FACE-181717?logo=github)](https://github.com/biometric-community/WIDER-FACE)
        [![Access: public](https://img.shields.io/badge/access-public-0e8a16.svg)](http://shuoyang1213.me/WIDERFACE/)

        **WIDER FACE** — a large-scale face detection benchmark with rich event / scale / occlusion variation.

        - **Dataset repository**: https://github.com/biometric-community/WIDER-FACE
        - **Upstream source**: http://shuoyang1213.me/WIDERFACE/
        - **License (helpers / docs)**: CC BY 4.0 (see [`LICENSE`](LICENSE))
        - **License (data)**: upstream terms — this packaging does **not** relicense the data


        | Field | Value |
        |-------|-------|
        | Catalog id (tbiom) | `wider-face` |
        | Category | `face-detect` |
        | Access | `public` |
        | Upstream homepage | http://shuoyang1213.me/WIDERFACE/ |

        ## TL;DR

        - **Task**: face detection
        - **Access**: **public**
        - **This mirror**: documentation + download helpers only (no bulk payload in git)
        - **Notes**: Images + annotations are distributed via Google Drive on the project page (multi-GB). This mirror ships docs/helpers only.

        ## Table of contents

        - [Download](#download)
        - [Dataset structure](#dataset-structure)
        - [Known issues and caveats](#known-issues-and-caveats)
        - [License](#license)
        - [Citation](#citation)
        - [Contact](#contact)

        ## Download

        ### Clone this repository

        ```bash
        git clone git@github.com:biometric-community/WIDER-FACE.git
        cd WIDER-FACE
        ```

        ### tbiom monorepo helper

        ```bash
        bash projects/datasets/scripts/download_wider_face.sh
        ```

        Then follow the printed upstream steps and place archives under `projects/datasets/wider-face/`.

        ## Dataset structure

        ```text
        WIDER-FACE/
        ├── README.md
        ├── LICENSE                 # helpers / docs (CC BY 4.0)
        ├── .gitignore
        └── extracted/              # local only after you download (gitignored)
        ```

        ## Known issues and caveats

        - Upstream hosts / Drive quotas often block fully automated downloads.
        - Do not commit multi-GB payloads to this GitHub mirror.

        ## License

        Helpers/docs: CC BY 4.0. Dataset files: upstream license / access agreement.

        ## Citation

        ```bibtex
        @inproceedings{yang2016wider,
  title={WIDER FACE: A Face Detection Benchmark},
  author={Yang, Shuo and Luo, Ping and Loy, Chen Change and Tang, Xiaoou},
  booktitle={CVPR},
  year={2016}
}
        ```

        ## Contact

        - Upstream: http://shuoyang1213.me/WIDERFACE/
        - Packaging: https://github.com/biometric-community/WIDER-FACE/issues

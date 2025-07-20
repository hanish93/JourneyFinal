# JourneyTextApp (flat layout)

Console tool that turns a driving video into a concise journey narrative.

## Install (CUDA GPU)

```bash
git clone https://github.com/<your‑user>/JourneyTextApp.git
cd JourneyTextApp

# 1️⃣  Pick the torch build that matches your CUDA (example: 12.1)
pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu121

# 2️⃣  Everything else
pip install -r requirements.txt

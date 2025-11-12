# JTC AI Day – Project Runway ✈️

GroundCrew.AI is a hands-on hackathon experience that guides participants through building a pre-boarding Copilot Studio agent for Quantum Corp’s newest hire, Alex. The site delivers the mission narrative, workshop flow, and step-by-step lab guides that teams use during the JTC AI Day challenge.

## 🌍 Scenario
- **Theme:** Project Runway – Mission Smooth Landing  
- **Agent:** GroundCrew.AI, a Copilot Studio assistant that verifies identities, collects headshots, answers HR questions, and orchestrates pre-boarding tasks before Day 1.
- **Story Arc:** Teams join the Runway Control crew to ensure every new hire lands smoothly through proactive automation and knowledge experiences.

## 🗺️ Site Structure
| Page | Purpose |
| ---- | ------- |
| `index.html` | Landing page introducing the mission, GroundCrew.AI vision, audience, and CTA to begin the workshop. |
| `stages.html` | Curriculum-style overview of the flight plan with links to detailed stage guides. |
| `stage-1.html` | Stage 1 guide (Sign In) – log into Copilot Studio with demo credentials. |
| `stage-2.html` | Stage 2 guide (Build the Agent) – create the agent, upload knowledge bases, and validate responses. |
| `stage-3.html` *(planned)* | Set up Dataverse tables used throughout the mission. |
| `stage-4-*.html` *(planned)* | 2FA Identity Clearance sub-steps: build email check flow, OTP flow, and integrate with the topic. |
| `stage-5-*.html` *(planned)* | Crew ID Setup sub-steps: build headshot upload flow and integrate with the topic. |
| `stage-6.html` *(planned)* | Mission Test – run the full Alex end-to-end simulation. |

Each stage page reuses the shared navigation, hero layout, imagery, and footer to keep the experience consistent.

## 🛠️ Tech Notes
- Pure HTML/CSS + vanilla JS (React-like interactivity is handled inline for the landing page).
- Assets live under `/Images` for mascots, logos, and step-by-step screenshots.
- A lightweight Python virtual environment (`.venv/`) exists only for docx parsing during content creation.

## 🚀 Getting Started Locally
```bash
cd /Users/zafirmain/Desktop/JTC-AI-Day---Hands-on-lab
python3 -m http.server 8000
# Browse to http://127.0.0.1:8000/index.html
```
Stop the server with `Ctrl+C` when finished.

## 🙌 Credits
- Built for **JTC AI Day · Nov ’25**  
- Powered by **Microsoft Copilot Studio**  
- Hands-on guide authored by **Zafir — Solution Engineer, Microsoft**

Enjoy the mission and help Alex land smoothly! ✨


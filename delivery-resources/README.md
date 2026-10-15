# ILL392 - Delivery resources

## Build Agentic AI PostgreSQL Apps on Azure HorizonDB

This folder contains the presenter and attendee presentation decks and the guidance needed to run the **ILL392** lab session at the Microsoft Frontier Tour or re-deliver it at user groups, user enablement sessions, community events and other similar engagements.

## Who this guide is for

- **Lead presenters** delivering the 75-minute lab session on stage or in a hands-on lab room.
- **Proctors** supporting the lead presenters and assisting attendees during the lab session.
- **Community speakers/MVPs** re-delivering the lab session at user groups, user enablement sessions, community events, and other similar engagements.
- **Customers/attendees** participating in the lab session and following along with the instructions.

If you are an attendee working through the lab, start at the root [README](/README.md) and [instructions](/instructions/part-0-setup-azure-resources.md).

## Core materials

| Item | Link | Notes |
|---|---|---|
| Delivery deck | coming soon | Required URL |
| Session recording | [Recording](https://aka.ms/ft27/ill392/youtube) | Optional URL when available |
| Attendee landing page | [Session README](/README.md) | Public starting point |
| Workshop/lab instructions | [Instructions](/instructions/README.md) | Lab instructions for attendees |

## Delivery checklist

- Review the session README
- Review the attendee instructions
- Open the deck
- Review the presenter guidance below
- If delivering this session using a preprovisioned environment, ensure it is set up and accessible before the session begins.
- Validate any required environment or setup

## Session preparation

- Review the attendee entry point from the root README.
- Review the delivery deck.
- Validate the required environment and setup.

## Run of show

The lab session is divided into multiple sections including 17 slides to cover key concepts and hands-on exercises.

### Timing

| Time | Description|
|---|---|
| 00:00 - 02:00 | Introduction and overview of the lab session |
| 02:00 - 15:00 | The Caldova overview and key concepts |
| 15:00 - 70:00 | Lab Steps & Completion |
| 70:00 - 75:00 | Wrap up & Q&A |

## Demo reproducibility

This hands-on lab uses the runnable notebooks in [`src/`](/src/) rather than a separate live demo. Before delivery, complete the environment steps in [`setup/SETUP.md`](/setup/SETUP.md), confirm the required Azure resources and environment values are available, and run the notebooks in order:

1. `1-data-setup.ipynb`
2. `2-app-development.ipynb`
3. `3-diagnostics.ipynb` when diagnostics or troubleshooting are needed

Use the attendee guidance in [`instructions/`](/instructions/) to verify the database connection and the transition from setup to the notebook exercises.

## Support

Content owner or contact: [Ismaël Mejía](https://github.com/iemejia) or open an issue on this repository and tag him for assistance.

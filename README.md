# Microsoft Teams Governance & Implementation Pilot

## Project Overview

This project is a hands-on Microsoft 365 governance and adoption pilot built in a live Microsoft 365 tenant.

The objective was to design, implement and test a controlled Microsoft Teams environment before a hypothetical wider organisational rollout. The project focused on governance, access control, SharePoint integration, collaboration, external sharing, user testing and adoption.

The pilot was structured around a project lifecycle:

**Discovery → Planning → Implementation → Testing → Governance → Adoption → Handover**

> This is a self-directed technical project and not a production deployment for an external organisation.

---

## Project Objectives

The pilot was designed to:

- Create a structured Microsoft Teams collaboration environment.
- Establish clear ownership and membership controls.
- Test standard and private channel behaviour.
- Validate permissions from both administrator and user perspectives.
- Understand the relationship between Teams and SharePoint Online.
- Review and configure external file-sharing controls.
- Test collaboration and messaging functionality.
- Document governance standards.
- Consider user adoption, support and project handover.

---

## Technologies Used

- Microsoft Teams
- Microsoft 365
- SharePoint Online
- Microsoft 365 Groups
- Microsoft 365 Admin / SharePoint Admin Center
- Microsoft Word
- Microsoft Entra ID user accounts

---

## Pilot Environment

A private Team named **Teams Implementation Pilot** was created as the controlled pilot environment.

The Team contained:

- **General** – general collaboration, governance information and pilot communications.
- **Project Delivery** – implementation activities, testing, issues and project documentation.
- **Project Leadership** – private channel for governance, risks, decisions and sensitive project discussions.

A separate test account was used to validate the environment from an end-user perspective rather than relying solely on administrator configuration.

---

## Governance and Access Control

The project tested several governance controls including:

### Team Membership

Team membership and ownership were reviewed to understand how access to the Team and its underlying SharePoint resources is controlled.

### Private Channels

A dedicated **Project Leadership** private channel was created.

Testing confirmed that:

- Authorised users could access the private channel.
- A standard Team member without private-channel membership could not see the channel.
- The private channel generated a separate SharePoint channel site.
- The separate site maintained its own membership and administration controls.

This demonstrated practical separation of sensitive project information from general Team collaboration.

### SharePoint Permissions

The SharePoint site associated with the Team was reviewed to understand the relationship between Microsoft Teams membership and SharePoint permissions.

Permission groups included:

- Owners
- Members
- Visitors

This demonstrated the underlying SharePoint permission model supporting Teams file collaboration.

---

## External Sharing Controls

External sharing settings were reviewed through the SharePoint Admin Center.

The pilot examined:

- Anonymous/Anyone sharing
- New and existing guests
- Existing guests
- Organisation-only sharing
- Default sharing link behaviour

For the private **Project Leadership** channel site, external file sharing was restricted to:

**Only people in your organization**

The default sharing link was also configured to:

**People with existing access**

This provided a least-privilege approach for sensitive project information and reduced the risk of accidentally granting access through newly created sharing links.

---

## Teams and SharePoint Integration

The pilot demonstrated the relationship between Microsoft Teams and SharePoint Online.

A governance document was created and stored through the Team's shared document library. The document was then surfaced directly within Teams as a tab.

This demonstrated how Teams can provide the collaboration interface while SharePoint provides the underlying document storage and permissions framework.

---

## Collaboration Testing

The environment was tested from an end-user account to validate the actual user experience.

Testing included:

- Channel posts and threaded conversations
- Message editing
- Message deletion
- Important and urgent messages
- URL previews
- Message translation
- Immersive Reader
- Code snippets
- GIF/sticker functionality
- Praise
- Reactions
- Shared document access

Testing from a separate account helped confirm that configured functionality behaved as expected for users.

---

## Governance Documentation

A governance guide was created for the pilot covering areas including:

- Team ownership
- Membership
- Permissions
- External access
- Document collaboration
- Sharing
- Lifecycle management
- Consistent use of Microsoft Teams

The governance document was made accessible directly from within the Team to support users and future handover.

---

## Adoption and Handover

Technical implementation alone does not ensure successful Microsoft 365 adoption.

The pilot therefore included an adoption and handover approach covering:

- User guidance before wider rollout
- Pilot feedback
- Recording issues identified during testing
- Reviewing feedback before implementation
- Confirming ownership and permissions
- Confirming external-access controls
- Confirming lifecycle controls
- Providing user guidance and support

The intention is to move from technical implementation into a controlled and supportable operational service.

---

## Key Risks Considered

The project considered common Microsoft Teams governance risks such as:

- Uncontrolled access to sensitive information
- Excessive external sharing
- Incorrect Team or channel membership
- Orphaned Teams without appropriate ownership
- Permissions becoming inconsistent over time
- Team and channel sprawl
- Inactive Teams remaining indefinitely
- Users not understanding governance requirements
- Poor adoption caused by insufficient guidance or training

These risks informed the governance and access-control decisions used throughout the pilot.

---

## Project Outcome

The pilot successfully demonstrated a structured Microsoft Teams environment with practical governance controls and documented testing.

The project provided hands-on experience across both the technical and project-delivery aspects of Microsoft 365 collaboration, including:

**Teams administration | SharePoint Online | Permissions | Private channels | External sharing | Governance | User testing | Adoption | Handover**

---

## Evidence

The implementation was documented throughout the project with screenshots covering configuration, permissions, testing, SharePoint integration and governance controls.

Selected evidence will be included in this repository while avoiding unnecessary exposure of tenant information.

---

## Lessons Learned

The project reinforced that Microsoft Teams governance extends beyond creating Teams and channels.

Effective governance requires consideration of:

- Who owns collaboration spaces.
- Who should have access.
- How sensitive information is separated.
- How SharePoint permissions support Teams.
- How external sharing is controlled.
- How users understand the expected way of working.
- How Teams are reviewed throughout their lifecycle.
- How the service is transitioned into ongoing support.

The pilot also demonstrated the importance of testing controls using a separate user account rather than assuming administrative configuration produces the intended end-user experience.

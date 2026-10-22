# Particle IoT: first captured event — internal launch brief

## Review gate

**Internal review only. Don't draft public claims until product signs off.**

Proposed next step: validate a documentation-led launch around capturing your first Particle event.

## Evidence for product review

### Availability and supported behavior

Release notes announce a Particle IoT warehouse source with event capture.

Ask product to confirm current availability, rollout status, and access requirements. Request approval of the supported event flow and its boundaries.

### Shipping release

The latest PostHog/posthog release is desktop-v0.61.802.

Ask product to confirm Particle's shipping release explicitly. Don't infer it from the latest release.

### Existing documentation

PostHog's docs are at posthog.com/docs.

Ask product to identify any existing Particle setup guide. Request its canonical link before commissioning another guide.

## Product sign-off checklist

Ask the Particle product owner to complete these checks:

- [ ] Confirm availability and any access prerequisites.
- [ ] Identify the release that shipped Particle event capture.
- [ ] Approve the supported-behavior description.
- [ ] Confirm setup requirements, authentication, and permissions.
- [ ] Provide a tested path from source configuration to a captured event.
- [ ] Specify how you verify that the event arrived successfully.
- [ ] Confirm supported payloads, identity mapping, and any delivery constraints.
- [ ] Identify existing documentation, or approve a new setup guide.
- [ ] Approve the scope of public claims before drafting begins.

Record the approver, decision, supporting links, and unresolved questions here:

- Product approver: _Awaiting assignment_
- Decision: _Awaiting sign-off_
- Supporting evidence: _To be supplied_
- Unresolved questions: _Complete the checklist above_

## Proposed documentation-led launch

After product approval, draft a first-captured-event guide using the verified setup path.

Include prerequisites, configuration, a tested event example, verification, and troubleshooting. Link existing documentation rather than duplicating it.

Keep availability and shipping-release claims blocked until product confirms them. Don't add endpoints, limits, flags, or delivery guarantees without supporting evidence.

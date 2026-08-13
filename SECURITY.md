# Sutura security policy

## Supported releases

HuntSoft LLC provides security fixes for the latest eligible Sutura release. Subscription customers receive releases
while their update entitlement is active. Perpetual customers receive releases whose release date falls within their
signed update window. Reader releases may be updated without charge.

Prerelease builds have a bounded support envelope and may receive a replacement release instead of a patch for an older
version. Experimental Linux and macOS artifacts are not supported platforms until their qualification status changes.

## Report a vulnerability privately

Do not open a public issue for a suspected vulnerability. Use GitHub's private vulnerability-reporting form in the
public [`HuntSoftLLC/Sutura-Releases`](https://github.com/HuntSoftLLC/Sutura-Releases/security/advisories/new)
repository. Private vulnerability reporting is enabled there and must remain enabled for every public candidate and
stable release. Customers may instead use the private support channel identified in their purchase or support agreement.

Never include patient, customer, credential, private-key, signed-license, or production-endpoint data. Reproduce with
synthetic input and include only the affected Sutura version, edition, platform, impact, minimal steps, and any safe
proof of concept.

## Response targets

HuntSoft LLC targets acknowledgment within three business days, initial triage within ten business days, and a status
update at least every fourteen calendar days while a confirmed issue remains open. These are response targets rather
than guaranteed remediation dates. Severity, exploitability, affected support windows, and the safety of a fix determine
release timing.

HuntSoft LLC will coordinate disclosure with the reporter. Please allow a reasonable remediation period before public
disclosure. A release advisory will identify affected versions, mitigations, and fixed versions without publishing
sensitive customer information.

## Security boundaries

Sutura processes healthcare representations but is not a medical device, clinical decision system, production interface
engine, or unattended delivery service. Use synthetic or properly de-identified data. License verification is offline
and collects no device fingerprint or activation count. The manual update check sends no document or license fields and
never downloads or installs software.

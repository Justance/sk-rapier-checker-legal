# Privacy Policy for sk_rapier_checker

**Effective date:** November 2, 2026  
**Last updated:** November 2, 2026

This Privacy Policy describes how the private Discord application
`sk_rapier_checker` (the **Application**) processes information. The Application
is operated by the owner of this repository (the **Operator**) and is intended
only for Discord servers and channels that have expressly authorized it.

## 1. Purpose and scope

The Application is a read-only signal listener. It examines messages in a small
allowlist of authorized Discord channels to identify relevant retail product
links and release notices. A detected link is only a signal for separate safety
and availability checks; a Discord message does not authorize a purchase.

The Application does not automate a normal Discord user account and does not
access channels in which its bot account lacks permission.

## 2. Information processed

For allowlisted channels only, the Application may receive and transiently
process:

- Discord server, channel, and message identifiers;
- message creation or update timestamps;
- message text, embeds, attachment metadata, and components when supplied by
  Discord's API;
- public product URLs, product identifiers, and release terms extracted from a
  message; and
- operational information such as receipt time, deduplication status,
  connection health, and processing outcome.

The Application is designed not to persist complete message bodies, usernames,
display names, avatars, member lists, or attachment contents. It does not
intentionally collect direct messages, passwords, Discord user tokens, email
addresses, payment information, addresses, phone numbers, or retail-account
credentials.

## 3. How information is used

Information is used only to:

- determine whether a message came from an approved server and channel;
- extract and validate relevant public product links;
- prevent duplicate processing;
- trigger a separate, conservative product-availability check;
- maintain connection and processing reliability; and
- investigate errors, abuse, or security incidents.

Discord message content is not used to train machine-learning or artificial
intelligence models. The Operator does not sell personal information or use it
for advertising or user profiling.

## 4. Storage and retention

Message content is intended to remain in memory only long enough to extract and
validate relevant signals. Sanitized operational records may contain server,
channel, and message identifiers, timestamps, extracted product links, hashes,
and outcomes.

Sanitized message-processing records are retained for no more than 30 days by
default. Server and channel configuration identifiers may be retained while the
Application remains authorized for those locations. When the Application is
removed or authorization is withdrawn, associated configuration and operational
records will be deleted within 30 days, except where temporary backups or legal
obligations require a short additional period.

## 5. Sharing and third parties

The Operator does not sell or rent information processed by the Application.
Information may be disclosed only:

- when required by law;
- to protect the security or integrity of the Application; or
- to a service provider strictly necessary to operate the Application and bound
  to protect the information.

An extracted public retail URL may be requested from the relevant retailer to
check availability. Discord usernames, message text, and Discord identifiers are
not intentionally included in that retailer request.

The Application relies on Discord and may interact with public retailer pages.
Those services process information under their own policies.

## 6. Security

The Application uses a dedicated Discord bot account, channel allowlists,
least-privilege permissions, local secret storage, sanitized logs, and bounded
processing. No method of storage or transmission is completely secure, but the
Operator limits collection and access to what is necessary for the stated
purpose.

## 7. User choices and deletion requests

Server owners and administrators may remove the Application or revoke its
channel access at any time. A user or server administrator may request access,
correction, or deletion of relevant retained information by opening an issue in
this repository:

<https://github.com/Justance/sk-rapier-checker-legal/issues>

Do not include passwords, tokens, private message contents, or other sensitive
information in a public GitHub issue. The Operator may request limited
verification that the requester controls the relevant server, channel, or
message before acting on a request.

## 8. Children's privacy

The Application is not directed to children and does not knowingly collect
personal information from children. If such information is believed to have
been processed, contact the Operator so it can be removed.

## 9. Changes to this policy

This policy may be updated when the Application's functionality or legal
obligations change. The current version and its effective date will remain
publicly available at this URL.

## 10. Contact

Questions or privacy requests may be submitted through the repository's issue
tracker:

<https://github.com/Justance/sk-rapier-checker-legal/issues>


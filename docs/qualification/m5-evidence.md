# M5 qualification evidence — `.github`

- Evidence window: 2026-09-26T20:38:00Z–2026-09-26T21:03:00Z
- Exact tested source: `e0018afca66f2884a9f7654a8c2cba01e2fc5f04`
- Environment: development control plane; GitHub Actions consumers plus clean Hetzner checkout `/home/krille/work/.github`
- Protected consumer evidence: Axiom run `36268795759`, demo runs `36267065085`, `36267065132`, `36267065135`, `36267065167`, NovaInvest runs `36268800956` and `36268801008`

## Gap, blind-spot and negative-space analysis

The missing canonical Hetzner checkout was created from the personal repository and verified at the exact SHA. The reusable workflow has no meaningful standalone deployment; its accepted development deployment is the set of protected exact-pin consumer executions above. A direct `.github` Actions run is therefore not invented. Historical former-owner text remains evidence only; active caller pins use `kristoffersodersten/.github`.

No production activation, secret value, review, or organization deletion is claimed. Finite fixtures cannot cover every future GitHub event or platform change.

## Adversarial profile and recovery

The traceability validator accepted the canonical fixture and rejected missing-ID, wrong-ID and incomplete-incident fixtures. Repository inventory JSON parsed. A full Git bundle was restored into an isolated checkout; strict fsck and exact-HEAD comparison passed. Consumer runs prove authorization/identity, hostile metadata rejection, stale-state rejection, dependency failure visibility, and restartable execution. UI/accessibility and abusive-user domains are not applicable to this policy repository.

Result: 4 deterministic local cases passed, protected consumers passed, one bundle recovery passed, zero failed or blocked.

# Standalone migration provenance

Project MRI was initially packaged temporarily inside the Moon-Source repository during the InfraJam 2026 activation pass because the available execution connector could not create a new GitHub repository.

After Moon created [`luahelenammc/Project-MRI`](https://github.com/luahelenammc/Project-MRI), the verified Project MRI implementation was migrated here as its canonical standalone home. The prior Moon-Source placement is historical transport topology, not a dependency of this repository.

## Migration source

- Temporary path: `luahelenammc/Moon-Source/projects/project-mri`
- Source repository: [`luahelenammc/Moon-Source`](https://github.com/luahelenammc/Moon-Source)
- Source HEAD at migration: [`bf027ab`](https://github.com/luahelenammc/Moon-Source/commit/bf027ab886a9201ef15d76148b119358fa220c4f)
- Historical PRs: [#75](https://github.com/luahelenammc/Moon-Source/pull/75), [#76](https://github.com/luahelenammc/Moon-Source/pull/76), [#77](https://github.com/luahelenammc/Moon-Source/pull/77)
- Migration date: 2026-09-14

The migration uses a clean import rather than a history rewrite. This preserves the working public body and makes the topology correction explicit while leaving Moon-Source history honest and untouched.

## Boundary

Project MRI is a derived, independently runnable reference implementation informed by Moon Source’s public context-governance principles. It does not import private Moon sources, hospital or patient data, credentials, connector data or private heuristics. Moon retains final authority over authorship, licensing, publication and external commitments.

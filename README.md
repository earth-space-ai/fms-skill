# FMS Skill

Progressive-disclosure skill for the [GFDL Flexible Modeling System](https://github.com/NOAA-GFDL/FMS) (FMS), the Fortran framework underlying GFDL's MOM6, AM4, CM4, ESM4, SHiELD, and SPEAR models.

> **Skill author:** Koutian Wu (ktwu01@gmail.com)
> **Skill version:** 0.1.0-scaffold

> ⚠️ **Disclaimer — please read before using this skill.**
> This skill is **not a gold-standard reference**. It is a helper that lowers
> the barrier for new users to **get their hands dirty** with the model. AI
> agents (and the humans drafting this material) make mistakes; commands, file
> paths, namelist options, and physics explanations here can be wrong,
> incomplete, or out of date. **Always cross-check with the official model
> documentation, the source code, and a human expert before trusting any
> output for research, publication, or operational use.**

## What This Is

A guide to FMS for anyone working inside a GFDL model: diag_table configuration, domain decomposition, parallel I/O, coupling, time management, and common build/run errors.

## Status

Scaffold. Module layout, build systems, and key rules verified against the cloned `NOAA-GFDL/FMS` tree. Operational depth being filled in.

## Related skills in this org

- [mom6-skill](https://github.com/earth-space-ai/mom6-skill)
- [gfdl-fv3-skill](https://github.com/earth-space-ai/gfdl-fv3-skill)

## License

MIT (skill content). FMS is moving to Apache 2.0 with the 2025.04 release.

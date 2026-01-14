# ⚠️ Repository Archived

> **This repository has been archived and is no longer maintained.**
>
> **All specifications have moved to the unified DataJoint documentation:**
>
> 🔗 **https://docs.datajoint.com/reference/specs/**

---

## Where to Find Content

All specifications from this repository have been migrated to the unified documentation for DataJoint 2.0+:

| Spec Content | New Location |
|--------------|--------------|
| **All Specifications** | [Reference/Specs](https://docs.datajoint.com/reference/specs/) |
| Table Declaration | [Table Declaration Spec](https://docs.datajoint.com/reference/specs/table-declaration/) |
| Query Algebra | [Query Algebra Spec](https://docs.datajoint.com/reference/specs/query-algebra/) |
| Type System | [Type System Spec](https://docs.datajoint.com/reference/specs/type-system/) |
| Data Manipulation | [Data Manipulation Spec](https://docs.datajoint.com/reference/specs/data-manipulation/) |
| AutoPopulate | [AutoPopulate Spec](https://docs.datajoint.com/reference/specs/autopopulate/) |
| Codec API | [Codec API Spec](https://docs.datajoint.com/reference/specs/codec-api/) |
| Semantic Matching | [Semantic Matching Spec](https://docs.datajoint.com/reference/specs/semantic-matching/) |

## What Changed

### Specifications
- **Location:** Specifications now live in `datajoint-docs/src/reference/specs/`
- **Format:** Markdown format for better integration with documentation
- **Version:** Updated for DataJoint 2.0+ baseline
- **Organization:** Part of unified Reference section

### Enhancement Process
- **Old:** DSEP (DataJoint-Specs Enhancement Proposals) process **[Deprecated]**
- **New:** RFC (Request for Comments) via GitHub Discussions
  - [datajoint-python Discussions](https://github.com/datajoint/datajoint-python/discussions)
  - [datajoint-docs Discussions](https://github.com/datajoint/datajoint-docs/discussions)

See the [Contributing Guide](https://docs.datajoint.com/about/contributing/) for the new RFC process.

## New Documentation Structure

The DataJoint documentation follows the [Diátaxis](https://diataxis.fr/) framework:

- **[Tutorials](https://docs.datajoint.com/tutorials/)** — Learn by building
- **[How-To Guides](https://docs.datajoint.com/how-to/)** — Task-oriented guides
- **[Explanation](https://docs.datajoint.com/explanation/)** — Concepts and design
- **[Reference](https://docs.datajoint.com/reference/)** — Specifications and API (replaces this repo)

## Purpose of DataJoint Specs

The **DataJoint Specs** establish the **standards, conventions, and best practices** for designing and managing **DataJoint pipelines**.
These specifications ensure **consistency, scalability, and interoperability** across different scientific workflows and computing environments.

By following the **DataJoint Specs**, users and developers can:
- Maintain **structured, reproducible data pipelines**
- Ensure **compatibility across different DataJoint implementations**
- Adopt **best practices** for schema design, data integrity, and computational workflows
- Provide a **foundation for future enhancements** while preserving backward compatibility

## Communicating Version Compatibility

DataJoint Specs evolve **independently** from **DataJoint implementations**.

- Each implementation release states the spec version it supports
- Spec releases include a compatibility table listing compliant implementations
- Deprecations and upcoming changes are announced in advance to allow for smooth adoption

Each implementation **aligns with a specific spec version**, ensuring compliance while allowing for **gradual adoption of new features**.

Example:
```
DataJoint Python v2.0.0 - Supports Spec v2.0
- Introduces unified stores configuration
- Redesigned fetch API
```

## Contributing

Contributions now go through the unified documentation repository:

- **Documentation:** [github.com/datajoint/datajoint-docs](https://github.com/datajoint/datajoint-docs)
- **Contributing Guide:** [docs.datajoint.com/about/contributing](https://docs.datajoint.com/about/contributing/)
- **Discussion (RFC):** [GitHub Discussions](https://github.com/datajoint/datajoint-python/discussions)

### Proposing Specification Changes

1. Open a **Discussion** in [datajoint-python](https://github.com/datajoint/datajoint-python/discussions) with `[RFC]` prefix
2. Discuss with community and maintainers
3. If accepted, submit a PR to [datajoint-docs](https://github.com/datajoint/datajoint-docs)
4. Specifications are updated in `src/reference/specs/`

## Migration to DataJoint 2.0

If you're using DataJoint 0.14.x or earlier:

📖 See the [Migration Guide](https://docs.datajoint.com/how-to/migrate-to-v20/)

For pre-2.0 documentation, visit [datajoint.github.io/datajoint-python](https://datajoint.github.io/datajoint-python).

## License

This project, including the DataJoint Specification document, is licensed under the [CC BY-SA 4.0 License](LICENSE.md).

## Support

- **Documentation:** https://docs.datajoint.com
- **Community:** [GitHub Discussions](https://github.com/datajoint/datajoint-python/discussions)
- **Issues:** [datajoint-docs issues](https://github.com/datajoint/datajoint-docs/issues)
- **Email:** support@datajoint.com

---

**Last Updated:** January 2026
**Archive Date:** January 2026

# DataJoint Specs

## Purpose

This repo manages the DataJoints Specs.

The **DataJoint Specs** establish the **standards, conventions, and best practices** for designing and managing **DataJoint pipelines**.
These specifications ensure **consistency, scalability, and interoperability** across different scientific workflows and computing environments.  

By following the **DataJoint Specs**, users and developers can:  
- Maintain **structured, reproducible data pipelines**.  
- Ensure **compatibility across different DataJoint implementations**.  
- Adopt **best practices** for schema design, data integrity, and computational workflows.  
- Provide a **foundation for future enhancements** while preserving backward compatibility.  

## License
The licensing for the specs is under review. **Please inquire before contributing or copying.**  


## Communicating version compatibility
DataJoint Specs evolve **independently** from **DataJoint implementations** 

* Each implementation release states the spec version it supports.
* Spec releases include a compatibility table listing compliant implementations.
* Deprecations and upcoming changes are announced in advance to allow for smooth adoption.

Each implementation **aligns with a specific spec version**, ensuring compliance while allowing for **gradual adoption of new features**.  

Each implementation release may claim which Specs verrsion it supports. For example: 
```
# DataJoint Python v1.2.0 - Supports Spec v2.2
- Backward-compatible with Spec v2.1.
```

## Specifications
- **[Version 2.0](SPECS_2_0.md)** – Draft (Estimated Acceptance: 2025-04-01)


## DataJoint-Specs Enhancement Proposals (DSEPs)  
* [DSEP Process](DSEP_process.md)
* DSEP Template [DSEP-xxx](DSEP/DSEP-xxx.md)

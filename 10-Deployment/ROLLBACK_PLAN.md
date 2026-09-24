# Rollback Plan Framework

## Professional basis
Release/operations practices.

This is a standards-informed personal framework, not a company standard and not an automatic compliance claim.

## Role
Senior Release/Operations Engineer

## Objective
Define how to safely revert a release when predefined failure conditions occur.

## Required context
- Deployment design
- Previous stable version
- Database changes
- Migrations
- Dependencies
- Rollback triggers
- Recovery constraints

## AI execution rules
- Do not invent facts or requirements.
- Separate facts, assumptions, recommendations, risks, decisions, and open questions.
- Use company/project standards when provided.
- Ask clarification questions when material ambiguity exists.
- Explain important trade-offs.
- Do not claim compliance without assessment.

## Process
1. Define triggers
2. Define rollback sequence
3. Assess data/schema reversibility
4. Define post-rollback validation
5. Define ownership/communication
6. Identify irreversible changes

## Output
- Triggers
- Rollback steps
- Data considerations
- Validation
- Communication
- Owners
- Limitations

## Quality review
- Check completeness and consistency.
- Check unsupported assumptions.
- Check requirement traceability.
- Check risks, constraints, and open questions.
- Check alignment with company/project requirements.

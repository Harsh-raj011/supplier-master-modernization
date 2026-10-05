# Outbound Supplier Interface

## Objective

Publish created or updated supplier information to downstream AP and procurement systems.

## Integration Flow

The integration:

1. Receives supplier information through a REST trigger.
2. Maps incoming supplier information to the target supplier request.
3. Invokes the Oracle Fusion Supplier REST service.
4. Uses the supplier REST resource to create or update supplier information.
5. Maps supplier fields such as supplier number, alternate name, supplier type, addresses and sites.
6. Runs the integration and verifies processing through the activity stream.

## Key Concepts

- REST trigger
- REST invocation
- Data mapping
- Oracle Fusion REST services
- Create/update supplier operation
- Integration monitoring

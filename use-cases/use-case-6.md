# USE CASE: 6 View a Employee's Details to Support Promotion Requests

## CHARACTERISTIC INFORMATION

### Goal in Context
As an *HR advisor* I want *to view and employee's details* so that *the employee's promotion request can be supported.*

### Scope

Company.

### Level

Primary task.

### Preconditions

We know the employees details.  Database is ready for details to be viewed.

### Success End Condition

Employees details can be viewed so that they are ready to be used to support promotion requests.

### Failed End Condition

Employees details cannot be viewed.

### Primary Actor

HR Advisor.

### Trigger

Employee requests a promotion.

## MAIN SUCCESS SCENARIO

1. Employee request is sent to the HR Department.
2. HR advisor searches employee to view details on system.
3. Details are ready to be viewed.

## EXTENSIONS

3. **Employee number is wrong**:
    1. HR advisor is informed the the employee number is incorrect.
    
## SUB-VARIATIONS

None.

## SCHEDULE

**DUE DATE**: Release 1.0

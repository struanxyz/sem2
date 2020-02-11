# USE CASE: 7 Delete an Employee's Details to stay Compliant with DPA

## CHARACTERISTIC INFORMATION

### Goal in Context
As an *HR advisor* I want *to delete an employee's details* so that the *company is compliant with data retention legislation.*

### Scope

Company.

### Level

Primary task.

### Preconditions

We know the employees details.  Database is ready for details to be updated.

### Success End Condition

Employees details can be deleted so that the company is in line with DPA.

### Failed End Condition

Employees details cannot be deleted.

### Primary Actor

HR Advisor.

### Trigger

Employee gives new details or leaves the company.

## MAIN SUCCESS SCENARIO

1. Employees trigger is sent to HR Department.
2. HR advisor searches employee to delete details on system.
3. Details are ready to be deleted.

## EXTENSIONS

3. **Employee number is wrong**:
    1. HR advisor is informed the the employee number is incorrect.
    
## SUB-VARIATIONS

None.

## SCHEDULE

**DUE DATE**: Release 1.0

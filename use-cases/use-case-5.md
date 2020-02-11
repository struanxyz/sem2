# USE CASE: 5 Add a New Employee's Details to the System

## CHARACTERISTIC INFORMATION

### Goal in Context
As an *HR advisor* I want *to add a new employee's details* so that *I can ensure the new employee is paid.*

### Scope

Company.

### Level

Primary task.

### Preconditions

We know the employees details.  Database is ready for new employees to be added.

### Success End Condition

New employee is added to system with all details so they are ready to be paid.

### Failed End Condition

Employees details fail to be added on system.

### Primary Actor

HR Advisor.

### Trigger

New employee details are sent to HR.

## MAIN SUCCESS SCENARIO

1. New employee details are sent to the HR Department.
2. HR advisor adds new employee details to system.
3. Details are ready so that the employee can be paid.

## EXTENSIONS

3. **Bank details do not exist**:
    1. HR advisor is informed the bank details do not match.
    
## SUB-VARIATIONS

None.

## SCHEDULE

**DUE DATE**: Release 1.0

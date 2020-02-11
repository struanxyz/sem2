# USE CASE: 2 Produce a Report on the Salary of Employees of a Given Department

## CHARACTERISTIC INFORMATION

### Goal in Context

As an *HR advisor* I want to *produce a report on the salary of employees in a department* so that *I can support financial reporting of the organisation.*

### Scope

Company.

### Level

Primary task.

### Preconditions

We know all staff details.  Database contains current employee salary data.

### Success End Condition

A report is available for HR to provide to finance.

### Failed End Condition

No report is produced.

### Primary Actor

HR Advisor.

### Trigger

A request for finance information is sent to HR.

## MAIN SUCCESS SCENARIO

1. Finance request salary information for all members of staff.
2. HR advisor extracts current salary information of all employees.
3. HR advisor extracts current salary information of all employees of the given department.
4. HR advisor provides report to finance.

## EXTENSIONS

3. **Role does not exist**:
    1. HR advisor informs finance no department exists.

## SUB-VARIATIONS

None.

## SCHEDULE

**DUE DATE**: Release 1.0

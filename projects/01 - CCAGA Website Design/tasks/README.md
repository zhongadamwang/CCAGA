# Task Management

## Purpose
Individual task files in GitHub issue format for team collaboration and project tracking.

## Workflow Integration
- **Task Creation**: Tasks generated from plan-derivetasks skill
- **GitHub Integration**: Task files can be imported as GitHub Issues
- **Team Collaboration**: Use GitHub Issues for discussion and feedback
- **Documentation Sync**: Export updated issues back to maintain project records

## Task File Structure
Each task follows GitHub issue markdown format:
```markdown
# Task Title

## Description
Detailed task description and context

## Acceptance Criteria
- [ ] Criterion 1
- [ ] Criterion 2
- [ ] Criterion 3

## Labels
- priority: high/medium/low
- type: feature/bug/enhancement
- component: frontend/backend/design

## Dependencies
- References to other tasks or external dependencies

## Estimated Effort
[Hours/Days/Points based on estimation methodology]
```

## Task Categories
- **T01-T09**: Project setup and planning tasks
- **T10-T19**: Requirements and analysis tasks  
- **T20-T29**: Design and architecture tasks
- **T30-T39**: Development tasks
- **T40-T49**: Testing and quality assurance tasks
- **T50-T59**: Deployment and launch tasks

## Tracking
- See [task-tracking.md](task-tracking.md) for overall progress
- Individual task status maintained in GitHub Issues
- Regular sync between GitHub and project documentation
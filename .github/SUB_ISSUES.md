# Managing Sub-Issues

This document explains how to create and manage sub-issues in the 1inch-docs repository.

## What are Sub-Issues?

Sub-issues are smaller, focused tasks that are created from a larger parent issue. They help break down complex work into manageable pieces.

## Creating a Sub-Issue

### Method 1: Using the Issue Template

1. Go to the [Issues tab](https://github.com/Ogruj098/1inch-docs/issues)
2. Click "New Issue"
3. Select "Sub-issue" from the template options
4. Fill in the template:
   - Link to the parent issue using `#issue-number`
   - Describe the specific task
   - List any sub-tasks
   - Define acceptance criteria
5. Submit the issue

### Method 2: Using Task Lists in Parent Issues

You can also create sub-issues by converting task list items in a parent issue:

```markdown
## Tasks
- [ ] #123 - Sub-issue for feature A
- [ ] #124 - Sub-issue for feature B
```

## Linking Sub-Issues to Parent Issues

Always link sub-issues to their parent issue using one of these methods:

1. In the sub-issue description: `Related to #parent-issue-number`
2. In the parent issue task list: `- [ ] #sub-issue-number - Description`
3. Using GitHub's "Development" section to link issues

## Best Practices

1. **Keep sub-issues focused**: Each sub-issue should address one specific task
2. **Use clear titles**: Prefix with `[SUB]` to indicate it's a sub-issue
3. **Update parent issues**: When a sub-issue is completed, check it off in the parent issue's task list
4. **Add labels**: Use the `sub-issue` label to help with organization
5. **Close dependencies**: Close sub-issues before closing the parent issue

## Example Workflow

1. Create a parent issue for a large feature
2. Break down the work into sub-issues using the sub-issue template
3. Reference each sub-issue in the parent issue's task list
4. Work on and complete sub-issues one at a time
5. Mark completed sub-issues in the parent issue
6. Close the parent issue once all sub-issues are completed

## Tools and Resources

- [GitHub Issues Documentation](https://docs.github.com/en/issues)
- [Using task lists](https://docs.github.com/en/issues/tracking-your-work-with-issues/about-task-lists)
- [Linking issues](https://docs.github.com/en/issues/tracking-your-work-with-issues/linking-a-pull-request-to-an-issue)

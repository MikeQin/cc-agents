## Summary

<!-- Provide a brief description of the changes in this pull request -->

## Type of Change

<!-- Mark the relevant option with an "x" -->

- [ ] 🐛 Bug fix (non-breaking change which fixes an issue)
- [ ] ✨ New feature (non-breaking change which adds functionality)
- [ ] 💥 Breaking change (fix or feature that would cause existing functionality to not work as expected)
- [ ] 📚 Documentation update
- [ ] 🎨 Style/formatting changes (no functional changes)
- [ ] ♻️ Code refactoring (no functional changes)
- [ ] ⚡ Performance improvements
- [ ] 🧪 Test additions or updates
- [ ] 🔧 Configuration changes
- [ ] 🤖 Agent configuration updates
- [ ] 🚀 CI/CD pipeline changes

## Related Issues

<!-- Link to related issues using "Fixes #123" or "Closes #123" -->

- Fixes #
- Related to #

## Changes Made

<!-- Provide a detailed list of changes -->

### Agent-Specific Changes
<!-- If this PR involves agent configurations, list the affected agents -->

- [ ] Will (PO) - Product Owner
- [ ] Mike (Architect) - System Architect
- [ ] Amy (Web UI Designer) - Web UI Designer
- [ ] Jennifer (Mobile UI Designer) - Mobile UI Designer
- [ ] Sarah (Security Engineer) - Security Engineer
- [ ] Jim (Web Developer) - Web Developer
- [ ] Bob (Mobile Developer) - Mobile Developer
- [ ] Luke (Backend Developer) - Backend Developer
- [ ] Vijay (QA Tester) - QA Tester
- [ ] Alex (DevOps Engineer) - DevOps Engineer
- [ ] code-reviewer - Code Review Specialist
- [ ] debugger - Debugging Specialist
- [ ] data-scientist - Data Analysis Expert
- [ ] github-initializer - Repository Setup Expert

### Files Modified
<!-- List the key files that were modified -->

- `file1.extension` - Description of changes
- `file2.extension` - Description of changes

## Testing

<!-- Describe the testing that has been performed -->

### Test Coverage
- [ ] Unit tests added/updated
- [ ] Integration tests added/updated
- [ ] Manual testing performed
- [ ] Installation script tested
- [ ] Agent configurations validated

### Test Environment
<!-- Describe where and how you tested -->

- **OS**: 
- **Claude Code Version**: 
- **Browser** (if applicable): 
- **Node.js Version** (if applicable): 
- **Python Version** (if applicable): 

### Test Results
<!-- Provide evidence of testing -->

```bash
# Example test commands run
./install-agents.sh --force
claude --design --agent po "test feature"
```

## Documentation

<!-- Check all that apply -->

- [ ] README.md updated
- [ ] CLAUDE.md updated (agent configurations)
- [ ] TUTORIAL.md updated
- [ ] Inline code comments added/updated
- [ ] API documentation updated (if applicable)
- [ ] Installation instructions updated

## Security Considerations

<!-- Address any security implications -->

- [ ] No sensitive information exposed
- [ ] Input validation implemented
- [ ] Security best practices followed
- [ ] Dependencies scanned for vulnerabilities
- [ ] Agent permissions reviewed

## Performance Impact

<!-- Describe any performance implications -->

- [ ] No performance impact expected
- [ ] Performance improvements included
- [ ] Performance testing completed
- [ ] Bundle size impact analyzed
- [ ] Memory usage considered

## Backward Compatibility

<!-- Address compatibility with existing installations -->

- [ ] Fully backward compatible
- [ ] Migration path provided for breaking changes
- [ ] Existing agent configurations preserved
- [ ] Installation script maintains compatibility

## Screenshots/Demo

<!-- Include screenshots, GIFs, or demo links if applicable -->

<!-- 
Example:
![Agent Demo](url-to-screenshot)
-->

## Checklist

<!-- Ensure all items are completed before requesting review -->

### Code Quality
- [ ] Code follows project style guidelines
- [ ] Self-review completed
- [ ] Code is well-commented
- [ ] No debugging code or console.log statements left
- [ ] All linting checks pass
- [ ] All tests pass

### Agent Framework
- [ ] Agent identification properly implemented
- [ ] Phase detection working correctly (Design vs Develop)
- [ ] Agent collaboration patterns maintained
- [ ] Tool assignments are appropriate
- [ ] Output structure follows conventions

### Repository Standards
- [ ] Branch is up to date with target branch
- [ ] Commit messages follow conventional commits
- [ ] No merge conflicts
- [ ] CI/CD pipeline passes
- [ ] Security scans pass

### Documentation
- [ ] Changes are documented
- [ ] Usage examples provided (if applicable)
- [ ] Agent usage patterns updated (if applicable)
- [ ] Breaking changes clearly documented

## Additional Context

<!-- Add any additional context, concerns, or notes for reviewers -->

## Review Focus Areas

<!-- Guide reviewers on what to focus on -->

Please pay special attention to:
- [ ] Agent configuration accuracy
- [ ] Tool assignment appropriateness
- [ ] Documentation clarity
- [ ] Installation process
- [ ] Backward compatibility
- [ ] Security implications

---

**For Reviewers:**
- Ensure agent configurations maintain the 14-member team structure
- Verify that phase detection (Design vs Develop) works correctly
- Test installation script changes in a clean environment
- Validate that agent identification and collaboration patterns are preserved
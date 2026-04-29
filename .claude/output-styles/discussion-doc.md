# Discussion & Documentation Mode

## Purpose
Help the user clarify their thinking through discussion without writing code. Create a minimal document capturing only what was actually discussed.

## Behavior During Discussion

1. **Focus on user's concerns**: Address only what the user brings up or is uncertain about
2. **No code modifications**: This is purely for thinking through problems, understanding options, or making decisions
3. **Capture silently, show periodically**: Keep brief running notes of what's been discussed and show them occasionally for verification
4. **Check in regularly**: Ask if the user is satisfied with the discussion and ready for the summary document
5. **Leave details undecided**: Don't elaborate or decide implementation details unless the user specifically wants to
6. **Support all outcomes**: Decision to do something, not do something, or just understanding something better - all valid

## Final Document

When the user confirms they're satisfied:

- Create a document in the current working directory (or specified location)
- Include ONLY what was actually discussed - no templates, no prescribed sections
- Could be 3 lines or 30 lines - whatever reflects the actual discussion
- Capture decisions, learnings, rejections with reasoning - whatever came up
- Use minimal formatting (markdown headings/bullets as needed for clarity)
- Zero verbosity - every line should have been explicitly discussed

## Starting Point

If user provides a rough draft, quickly understand what they've already decided and focus on helping clarify their remaining concerns.

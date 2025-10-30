# Workout App - Cardio Round Selection Bug

**Date**: October 2025  
**Status**: Partially fixed (functionality works, display still broken)

## Problem
When selecting exercises in cardio rounds, the app only displays the first exercise as selected, regardless of which exercise you actually click.

## Current Behavior
- Backend works: Changes to exercises are applied correctly
- Frontend bug: Display continues to show only the first exercise as selected
- This creates confusion about which exercise is actually selected

## Impact
This bug affects the user's ability to customize their cardio exercises. This may cause users to incorrectly document the exercises they performed or not complete cardio at all.

## Evidence
- Tested October 2025
- Bug appears to be mid-fix (backend updated, frontend pending)
- Exercise notes issue appears to be resolved

## Potential Test
Track whether users who encounter this display issue have lower cardio completion rates compared to users doing workouts without cardio rounds.

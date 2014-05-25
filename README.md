undo-experiments
================

Experiments with Mutation Observers vs. Object.observe(). Best tested in Chrome 36 beta +.

The basic idea is that we have a `contentEditable` area of which we would like to track all edits made such to enable Undo/Redo.
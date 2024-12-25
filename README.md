# PHP foreach Loop and unset() Unexpected Behavior

This repository demonstrates a subtle bug in PHP related to using `unset()` inside a `foreach` loop when iterating over arrays.

The issue arises because `unset()` modifies the array during iteration, potentially leading to unexpected skipped elements.  The provided code examples illustrate the problem and its solution.
# JavaScript Loose Equality (==) Bug

This repository demonstrates a common error in JavaScript where loose equality (==) is used to check for null or undefined values. This can lead to unexpected behavior when comparing values that are not strictly equal.

## Bug Description
The provided code uses loose equality (==) to check for null or undefined inputs, which can lead to unexpected results.  When you compare a value with loose equality, type coercion can happen, potentially resulting in unexpected true/false outcomes.

## Solution
The solution uses strict equality (===) to check for null or undefined inputs. Strict equality does not perform type coercion, thus preventing the unexpected behavior caused by loose equality.
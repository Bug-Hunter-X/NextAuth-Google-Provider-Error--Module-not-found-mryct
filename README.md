# NextAuth Google Provider Module Not Found

This repository demonstrates a common issue when using the NextAuth.js library with the Google provider in Next.js 15: the module `next-auth/providers/google` cannot be found.

## Problem

When attempting to implement Google authentication using the `next-auth/providers/google` provider, the application throws an error indicating that the module cannot be found, even if the package is correctly installed.

## Solution

The problem usually stems from an incorrect import path or version mismatch.  This repository provides a corrected import and also addresses potential version conflicts.  The solution involves ensuring the correct `next-auth` version and verifying the import path.
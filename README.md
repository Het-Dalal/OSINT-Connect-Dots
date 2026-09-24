# OSINT — Connect Dots

> OSINT CTF investigation and evidence reconstruction.

## Overview

This challenge required recovering access to a target account by
correlating publicly available information.

Rather than relying on a single clue, the investigation followed
the attributes explicitly required by the account-recovery workflow.

## Investigation Flow

Public Profile Clues
        ↓
Identity Correlation
        ↓
Employment & Location
        ↓
Recovery Form
        ↓
Temporary Access
        ↓
Authentication
        ↓
Flag

## Investigation

### 01 — Recovery Requirements

The recovery workflow was examined first to determine which identity
attributes needed to be established.

### 02 — Profile Reconnaissance

Public profile content was examined for occupation and contact clues.

### 03 — Employment Correlation

Profile information was correlated with employer information to
establish the company and job role.

### 04 — Birthday & Location

Public posts and employer information were used to establish the
remaining recovery attributes.

### 05 — Account Recovery

The collected attributes were submitted through the challenge's
recovery mechanism, which returned temporary access.

### 06 — Authentication

The temporary credential was used before expiration, resulting in
successful authentication and challenge completion.

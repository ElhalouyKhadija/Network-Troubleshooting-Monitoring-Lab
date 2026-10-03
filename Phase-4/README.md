# Phase 4 – Windows Firewall Inspection

## Objective

Inspect the Windows Firewall status and review the currently enabled firewall rules.

## 1. Firewall Profiles

The Windows Firewall profiles were inspected using `Get-NetFirewallProfile`.

All three profiles were enabled:

- Domain: `True`
- Private: `True`
- Public: `True`

## 2. Enabled Firewall Rules

The number of enabled Windows Firewall rules was checked.

A total of `239` enabled firewall rules were found.

## 3. Firewall Rule Actions

The enabled firewall rules were grouped by action.

The result showed:

- Allow: `239`

No enabled `Block` rules were returned by the tested query.

![Windows Firewall Status](phase4-firewall-status.png)

## Status

**Applied**

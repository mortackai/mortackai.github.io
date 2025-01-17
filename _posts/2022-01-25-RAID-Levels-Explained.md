---
layout: post
title: RAID Levels Explained
date: 2022-01-25
---

RAID stands for Random/Redundant Array of Independent Disks


NOTE: This is a "high" level review and more of a reminder to myself, which RAID means what. Don't take this info to the bank because I am taking some liberties with the technical stuff for the sake of brevity.


## RAID-0 Disk Striping
Combines all disks into "single" drive: no fault tolerance.

## RAID-1 Disk Mirroring
Mirrors the data between all disks in the pool: Fault tolerance is n-1 (n is number of drives in the pool).

## RAID-5 Striping with Parity
Four or more striped drives with single parity: Fault tolerance is one drive.

## RAID-6 Striping with double parity
Five or more striped drives with double parity: Fault tolerance is two drives.

## RAID-10 Striped and Mirrored
Combine RAID 0 and RAID 1, so it mirrors the data between striped drive sets.

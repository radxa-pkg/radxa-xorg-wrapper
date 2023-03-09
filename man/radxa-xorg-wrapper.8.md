# RADXA-XORG-WRAPPER (8)

## NAME

radxa-xorg-wrapper - Provide Radxa specific customization for X.org

## SYNOPSIS

**radxa-xorg-wrapper**

## DESCRIPTION

On Rockchip platform, sddm will launch X.Org with `-background none`.
However, this causes display issue with RGA.

radxa-xorg-wrapper will remove this argument from X.Org when running
from sddm.

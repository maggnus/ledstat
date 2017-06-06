ledstat - utility to change hard drives led status

Usage:

    ledstat (without options) - display all slots devices status and disk letter
    ledstat --locate=[on|off] enclosure/index - enable/disable indicator for requested device
    ledstat --locate=[on|off] all - enable/disable indicator all devices for all enclosures
    ledstat --locate=[on|off] detected - enable/disable indicator only for detected devices
    ledstat --locate=[on|off] undetected - enable/disable indicator for undetected devices

Examples:
    ledstat - display current status
    ledstat --locate=on sg24/12 - enable indicator
    ledstat --locate=off sg24/12 - disable indicator
    ledstat --locate=on all - enable indicator for all devices in all enclosures
    ledstat --locate=on detected
    ledstat --locate=off undetected

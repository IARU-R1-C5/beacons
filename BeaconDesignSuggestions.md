# IARU R1 VHF and UP Beacon Design Suggestion

## What frequency should I use?

In general on each and every band you have two beacon segments:

- local / personal beacons (power limited to EIRP of 10W)

and

- beacons

Dependendly on the EIRP, during the coordintaion we will discuss the frequency in one of those segments.

## How should I stabilize the frequency of the beacon?

As you know one of the main historical reasons for beacons to exist was to check the frequency of your radio. Suggested method of frequency stabilization are GPS or OCXO with precision on the target band of less than 100Hz (TBD).

## What mode should the beacon run?

This guideliness are written in 2025, which means that suggested mode of beacon is MIXED, CW + MGM. Why? To enable development of automated propagation conditions measurments and still allow non-computer decode.

Please note that dependendly on the band your beacon transmission bandwidth should be limited to 500 or 1000Hz.

## What CW method should be used?

Most commonly used are A1A and F1A, usually in MIXED modes its easier to use F1A.

## What MGM mode should be used?

Commonly used digital modes for beacons are:

JT4, Q65 and PI4.

But please note that digital mode should be easy to decode by available software.
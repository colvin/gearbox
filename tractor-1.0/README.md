# tractor-1.0

## Issues

- Preventing lateral movement of the driver couplers

## Design

First gearbox design. Targets a small, home-made tractor. Low speed, high
torque. 2 gears (hi/lo) with reverse.

Engine output shaft with fixed (keyed) v-belt pulley drives a v-belt pulley
that is the input to the gearbox. The belt is slack until engaged by a
tensioner pulley, forming the first-stage clutch.

Input to the gearbox is through a fixed v-belt pulley. The ratio between the
engine output pulley and the gearbox input pulley forms the first stage gear
reduction.

The gearbox input drives the Hi/Lo unit. This unit allows switching between two
output chain sprockets, each with a different ratio. The Hi/Lo switching
coupler is fixed to the middle of the input shaft. It is fixed in terms of
rotation, but can be moved laterally along the shaft in both directions.  When
moved, it engages with either the Hi or Low coupler. Both of the Hi and Lo
couplers are fixed in the lateral direction but spin freely on the shaft by
means of bushings. The couplers include a roller chain sprocket. When either
the Hi or the Lo couplers are engaged, power is transmitted through their
respective sprockets and the other coupler spins freely on the shaft.

To reduce the outputs from the Hi/Lo unit from two to one, both the Hi and Lo
links drive sprockets that are fixed to a single shaft on the Hi/Lo aggregator
unit, from which fixed output sprocket transmits the power out.

The Hi/Lo aggregator output sprocket drives the Fwd/Rev unit. A fixed input
sprocket drives a shaft to which is fixed, in a manner identical to that of the
Hi/Lo unit, a switching coupler.

## Gear reductions

| Stage | Output | Input | Ratio |
| ---- | ------ | ----- | ----- |
| 1 | Engine | Gearbox | 6:1 |
| 2 | Hi/Lo Lo | Hi/Lo aggregator Lo | - |
| 2 | Hi/Lo Hi | Hi/Lo aggregator Hi | - |
| 3 | Hi/Lo aggregator | Fwd/Rev | - |
| 4 | Fwd/Rev Rev | Rev Jackshaft | - |
| 5 | Rev Jackshaft | Driveshaft Rev | - |
| 5 | Fwd/Rev Fwd | Driveshaft Fwd | - |

## Unit Details

### First stage clutch

This clutch uses an idler pulley to engage or disengage the engine output to
the gearbox. All power from the engine routes first through the gearbox, so
this clutch disengages _all_ of the PTOs at once. This is not only useful, it
is a primary safety feature allowing a single step to stop all activity without
requiring the engine to be stopped (including situations where the problem is
that the engine cannot be stopped).

The clutch requires that the position of the engine, the position of the
gearbox input shaft, the sizes of the pulleys, and the size of the belt be
matched such that the belt is retained on the pulleys but not under tension
when the clutch is disengaged.

### Hi/Lo aggregator

When either the Hi or Lo link is enagaged the opposite link's sprocket will be
driven by the aggregator shaft. This will in turn cause the corresponding
sprocket on the Hi/Lo unit to be driven, but because that coupler will be
disengaged from the Hi/Lo unit shaft, it will simply spin ineffectually.

## Part Details

### First stage clutch tensioner pulley

Tensioner pulley is an idler: it uses a roller bearing that rides on a fixed
shaft. It is engaged (moved into tensioning position) and disengaged (moved
into slack position) using a pivoting arm. The arm is pulled into a default
disengaged position using a spring. It is locked into the engaged position by
the end-user control lever such that any failure between the control lever and
the pulley causes the engine to be disengaged.

The idler pulley can be retained onto its fixed shaft using a retaining ring.
The groove doesn't need to be crisp, it could be ground into the shaft using
an angle grinder. This is probably better than using a bolt as the shaft with
a nylock nut to retain it.

### Hi/Lo switching coupler

The Hi/Lo switching coupler consists of two spider-style shaft couplers welded
together with their teeth facing outwards and their keyways aligned. It rides
along the key such that it cannot spin around the shaft but can move along the
shaft in either direction.

The plan is to use a keyed shaft. It may be necessary in the future (after R&D)
to use a doubly-keyed shaft, grind a second keyway into the shaft, or use a
splined shaft or portion of shaft. This depends on whether or how often the key
is sheared.

### Hi/Lo drive couplers

The Hi/Lo drive couplers consist of a spider-style shaft coupler welded
together with a roller chain sprocket with the coupler teeth facing outwards.
A bushing (bronze oil-embedded) sits between the unit and the shaft such that
it spins freely around the shaft.

The unit should not be allowed to move laterally along the shaft, lest it move
into engagement with the switching coupler. It may be possible to use a simple
retaining ring.

## Specifications

Engine output shaft
- 1"
- keyed

Engine output pulley
- 1" bore
- keyed
- 2.5" OD
- belt style B

First-stage clutch tensioner pulley
- 1/2" bore
- 3.1" OD
- belt style B

Gearbox input pulley
- 1" bore
- keyed
- 7.45" OD
- belt style B

Hi/Lo shaft
- 1"
- keyed
- 12" long

Hi/Lo shaft bearings
- x2
- 1" ID
- 2" OD
- Shielded
- 1/2" width
- R16-2Z

Hi/Lo switching coupler
- x2
- 1" bore
- keyed

Hi/Lo drive coupler
- x2
- 1 1/8" bore

Hi/Lo drive coupler bushing
- x4
- 1" ID
- 1 1/8" OD
- 1" long

Lo drive sprocket
- 1 1/8" bore
- 50 chain
- 12 tooth

Hi drive sprocket
- 1 1/8" bore
- 50 chain
- 12 tooth

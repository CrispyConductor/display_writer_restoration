# DisplayWriter Restoration Project 2026

![DisplayWriter Before Restoration](images/001_before_topdown.jpg)

This is a write-up with photos of my process to restore a vintage IBM DisplayWriter Beam Spring
keyboard.  The intent is to document the specific process I used, write down how I dealt with some of the
specific challenges I encountered with this board, and provide something of a guide for others
attempting similar projects.  There exist other write-ups of beam spring keyboard restorations;
here I try to provide some additional detail, fill in some of the gaps in other write-ups, and
add in additional discoveries.

## Dedication

Does a "dedication" even apply to a vintage keyboard restoration report?  Not sure, it seems a bit weird ...
but in this case, I do feel that a dedication is deserved:

This project is dedicated to my absolutely wonderful wife who has been incredibly patient with me,
not only tolerating this project, but supporting it; through weeks of a cacophony of switch clicks and
ultrasonic cleaner buzzing, and every flat surface in the house being consumed.

## Why?

Why, in 2026, am I spending so much time restoring a nearly-half-century-old keyboard?

As a long-time Model M user, I recently found out about the existence of beam spring keyboards, and knew I had
to give them a try.  The theoretical mechanics of the switch operation appeal to me.  In many ways, it seems to
be something of a "pure" version of what a keyboard switch "should" be, and I had to experience the type feel that
others have described.

I came across the Model F Labs project, and the easiest way to try a beam spring keyboard would be to order
one of their new reproduction keyboards.  Indeed, I have one on order!  But a few things kept gnawing at me
that led me to also want to restore an IBM original.

Ellipse's attention to detail appears to be remarkable, and testimonials have been very positive.  However,
a few reports describe that they don't quite match the feel - and definitely don't match the sound - of
the originals.  Notably, several users report that the reproduction beam spring switches are less smooth
than the originals.  Just speculating, I suspect this is an engineering trade-off related to Ellipse's efforts to shrink
the height of the switch while maintaining travel distance; it seems plausible that the reduced bearing
surface and reduced distance between stabilizing springs could impact the smoothness and "floating"
feeling I've heard described.  A shorter switch very clearly has numerous advantages in the modern world,
but I still felt like I needed to try an original.  And as soon as my MFL board arrives, I'll certainly
be posting reports on the comparison!

After deciding that I wanted to get a good original IBM beam spring keyboard, I had to determine which one.
I don't have the budget for a good-condition, fully-restored, or already-converted keyboard, so I found a
poor-condition unit on ebay that was in my price range.  I also have mixed feelings about removing working
keyboards from vintage computing systems, so the poor/for-parts condition of this keyboard made me feel a
bit better about that.

The keyboard I picked is the DisplayWriter keyboard.  The biggest reason is that is what I happened to find
in my price/condition range; but I probably would have picked a DisplayWriter regardless, just because its
layout can be most easily remapped to a modern one (minus the numpad, which I don't use much).

## Initial Keyboard Condition

The keyboard condition was listed as 'Used', but it would be more accurate to call it heavily-damaged, possibly
in the "for-parts" range.  The blurry ebay pictures showed several missing key caps, a crack in the case,
and a damaged connector; but not much else could be seen.

After the white whale arrived and I started a more detailed examination, it became clear that the keyboard had suffered a
catastrophic fall at some point in the past.  Based on the damage, it likely fell from a decent height,
landed at an angle on its face, then clattered around causing significantly more damage.  When it arrived,
the internals had shifted such that the case was impacting the keys on the bottom and left-hand
sides of the keyboard.

The damage included:

- 8 missing key caps
- 2 chipped key caps
- Badly bent up base pan and brackets
- Switch assembly wrenched out of bracket, twisting its metal tabs
- Crack clean through the case in one of the section dividers
- A number of badly bent switch stems
- A number of damaged switch sliders, including a few practically shattered
- A few miscellaneous other damaged switch components like a bent up return spring and sliced o-rings
- All the fun age-related deterioration associated with these boards

It was also quite dirty, but that is to be expected.  And the worst of the mess came from deteriorating
components of the keyboard itself; specifically the contamination shield and old foam.

The good news - there was practically no rust!  The base pan and switch plate were mostly corrosion-free;
just a couple isolated corrosion spots of stable dark-colored oxidation.  Rust treatment would have done
more harm than good, so I was able to avoid evapo-rust for the whole project; instead opting for spot
treatments to encapsulate the isolated small corrosion spots.  Silver linings!

## Restoration Objectives

I had two major objectives with this restoration:

1. Get an actual, functional, working keyboard that can be viably used as a daily-driver in a modern environment.
2. Preserve as much original history as possible.

I do enjoy the vintage nature of the keyboard and see it as something of a museum piece.  But I do intend to use
it extensively; so restoration decisions cannot compromise usability.  If usability ever directly conflicted with
historical preservation, I usually made the choice to prioritize usability.

The most difficult decision to make with the trade-off here was whether or not to retain the original caps-lock
mechanism.  The DisplayWriter has a cool and unique mechanical lock mechanism that would be very neat to preserve.
However, that key is an ideal place for a 'Ctrl' key, so I made the decision to remove the locking mechanism
and treat it as a normal switch.  But no permanent modifications are made and I'm retaining the original parts, so
it can always be reinstalled in the future.

In general, I wanted to make as few compromises as I possibly could.  After all, if a main reason to get such a
vintage keyboard is to have an original point of reference against modern reproductions, it's not really a fair
comparison unless it's restored to its best possible condition.  And this philosophy ended up costing me a lot
of additional time, as well as going in a few different directions from other restoration projects; though I hope the
result is worth it, and hopefully some of this work can benefit other restorers!

I also decided early-on to take an extreme amount of care during this restoration.  Reading other restoration reports,
damage (especially to the switches) is very common during such projects.  With the number of heavily-damaged switches
I already had, I couldn't afford to damage any more; so I developed some techniques for performing some operations
in a more controlled manner.  I believe it paid off.  Not only did I cause zero additional damage during any of
the procedures, but after all was said and done, I only ended up with a single non-functional switch from the original
set.

## A note about cleaning chemicals and processes

I have on hand a fair array of various solvents, oils, and cleaning chemicals; but for this project, I decided to
be more conservative.  These are historical materials, often of unknown composition, and sometimes made more
brittle or sensitive with age.

When I had a choice between using a more powerful chemical versus a less powerful one plus more time/elbow grease,
I usually picked the latter.  Unless I encountered particularly stubborn issues, most parts were cleaned with a
weak dish soap solution and a soft toothbrush or rag.

## Tools and Materials

This is an approximate list of tools and materials I used in the process.  It may not be 100% complete, but should cover the essentials.

### 3D Printed Fixtures and Parts

[Link to Models](https://www.printables.com/model/1883866-beam-spring-ibm-keyboard-switches-maintenance-tool)

- Switch removal tool: Depresses housing clips to remove switch from switch plate.
- Stem extraction fixture: Provides controlled force for disassembling beam spring switch.
- Fly spring go/no-go gauge: Simple check whether fly spring is in spec.
- Fly spring symmetry gauge: Checks whether fly spring legs are symmetric.
- Switch part cleaning racks: Safely contains small components for cleaning.
- Slider glue alignment fixture: Holds broken slider fragments tightly in position for glue-up.
- Switch housing lube mask: Ensures sprayed dry-lube only reaches intended areas.
- Switch stem insertion fixture: Allows controlled application of force during switch reassembly.
- Fly plate reassembly fixture: Safer and more repeatable "toothpick method" for assembling fly plate in-situ.
- Foam alignment pins: Helps align replacement foam for switch plate.
- Keycap chip inserts: 3d printed patches specific to the broken contours of my chipped keycaps.
- Replacement shift-lock mechanism inserts: Switch plate inserts replacing original shift-lock inserts, without dust ingress holes.
- Controller PCB support bracket: Additional support bracket for TH-xwhatsit controller PCB.

### Adhesives and Chemicals

- Thin liquid CA glue (Loctite brand): Various repairs, including casing and switch sliders.
- Gel CA glue (Loctite brand): Various larger-gap repairs, including keycap chips.
- 3M 72 spray adhesive: Repositionable soft-material adhesive for replacement switch plate foam.
- 3M 468MP adhesive transfer tape: Adhesive for plastic gasket strips.
- Starrett M1: Mild rust protectant for various metal pieces.
- Super Lube Dri-Lube PTFE spray: Light lubrication in switch housings.
- Isopropyl alcohol 99.9%: General cleaning solvent.
- Mild dishwashing detergent: First cleaning pass for most parts.
- Distilled water: Rinse of components before drying.
- Mineral spirits: Additional removal of old deteriorated foam.
- Goo gone: Additional removal of old deteriorated foam.

### Replacement Materials

- Ultra-soft EPDM foam sheet, McMaster #8647K102, 1/16" thick: Used for gasket strips along switch plate.
- Pre-cut DisplayWriter switch foam: Purchased on eBay (could have cut myself from foam sheet).
- Kapton tape: Labels on switch housings.
- Fine-tip permanent marker: Labels on switch housings.
- Masking tape: Masking and various uses.
- Plastic sheet: Protecting paper info card during case cleaning.
- Scotch tape: Encapsulating rubber feet.
- 3D printer filament: I used PETG for pretty much everything; more important for some things than others.

### Specific Spare Parts

- Replacement beam spring o-rings: Ebay purchase.
- Spare beam spring switches: Ebay purchase.
- Replacements for missing DisplayWriter keycaps: Ebay purchase.

### Cleaning Equipment

- Ultrasonic cleaner: Used for cleaning most small parts and switch components.
- Electric air duster (DataVac brand): Forced air drying, blowing water out of crevices.
- Soft toothbrushes: General scrubbing.
- Plastic razor blades and scraper: Scraping off old, degraded foam.
- Soft cloths and towels: Cleaning larger components, protecting surfaces.
- Paper towels: General cleanup, absorbing excess glue.
- Component organizer: Keep small components organized.
- Aluminum window screen: Used as part of small-parts ultrasonic cleaning bracket.
- Craft wire: Holding o-rings and return springs for cleaning.
- Vacuum cleaner: Removing degraded contamination shield fragments and misc dirt removal.

### Mechanical Tools

- Wire keycap puller: Keycap removal.
- Slotted screwdrivers: Case screws and misc prying.
- Nut drivers: Working with hex-head fasteners.
- Flat-jawed parallel pliers: Straightening bent metal components; I specifically used Knipex pliers wrench.
- Small smooth-jaw pliers: Various small-part manipulation.
- Tweezers: Various small-part manipulation.  Broad-tip versions are useful.
- Needle-nose pliers: Pin-modding card edge connector.
- Height gauge: Characterizing individual switch travel behavior.  I used a Mitutoyo brand height gauge.
- Flat surface: Reference surface for height measurements.
- Machinists' square: Checking squareness of base pan brackets.
- Plastic dead-blow hammer: Adjusting squareness of base pan brackets.
- Wood blocks: Back-stop for adjusting base pan brackets.
- Clamps: Holding down wood block back-stops.
- Vise: Holding PCBs for modification.
- Scalpel: Cutting replacement foam.
- Fine-grit sanding sponge: Smoothing glue repairs on slider bearing surfaces.
- Small files: Finishing cuts on PCBs and card edge connector.
- Drill bits: Manually punching gasket strip foam holes.
- Band saw: Cutting card edge connector to size.
- Toothpicks or small wires: For traditional fly spring attachment and adjustment.

### TH-Xwhatsit Controller Components

- PCBs: Ordered from JLC.
- Microcontroller module: SparkFun Pro Micro, DEV-12640, 5V / 16MHz
- DAC: Microchip MCP4921-E/P
- Quad comparator x2: Texas Instruments LM339N/NOPB
- Shift register x3: Texas Instruments SN74HC595N
- Card edge connector: EDAC 307-086-520-202
- Resistors, capacitors, diodes: Per TH-xwhatsit BOM.
- Pin headers & sockets
- PCB standoff & screws: Size per BOM.
- Ground wire: Ground connection to chassis.
- Crimp terminal: For ground connection.
- Micro-USB cable
- Electrical tape: Padding USB cable to fit the strain relief.

### Electronics Assembly Equipment

- Soldering iron
- Solder
- Soldering flux
- Flux cleaner/isopropyl alcohol
- Flush cutters
- Wire stripper
- Terminal crimp tool
- Multimeter
- "Helping hands"




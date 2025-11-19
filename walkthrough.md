# Polypad Compass Replication Walkthrough

I have successfully replicated the Mathigon Polypad compass tool, focusing on precise visual details and interactive behavior.

## Visual Features

### 1. Right Arm & Pencil Holder
- **Short Metal Arm**: The right leg is significantly shorter than the left, ending in a circular joint with a dark rivet.
- **Horizontal Bracket**: A gray bracket extends horizontally from the joint to hold the pencil.
- **Straight Pencil**: The pencil is held vertically (aligned with the compass axis), simulating a hinged attachment that keeps it upright regardless of the leg angle.
- **Alignment**: The bracket and joint are mathematically aligned to ensure a seamless mechanical connection.

### 2. Left Leg (Needle)
- **Asymmetric Taper**: The left leg features a "chisel" design:
  - **Straight Outer Edge**: The Left (Outer) side is straight and aligned with the compass axis.
  - **Tapered Inner Edge**: The Right (Inner) side tapers outwards.
- **Needle Tip**: A sharp black needle extends from the aligned Outer tip, creating a continuous straight line on the outside.

### 3. Hinge (Top)
- **Lock Shape**: The top hinge is a tall, tapered, dark "lock" shape with a silver rivet.
- **Extended Handle**: The handle at the top is elongated for better grip visuals.

### 4. General Style
- **Flat Vector Look**: Soft shadows were removed to match the clean, flat vector aesthetic of the reference.
- **Color Palette**: 
  - Pencil Body: Pinkish Red (`#be185d`)
  - Pencil Tip: Black (`#1e293b`)
  - Metal/Bracket: Gray (`#cbd5e1`)

## Interactions

The compass supports the following interactions, indicated by dynamic cursor changes:

- **DRAW**: Drag the **Pencil Tip** to draw circles/arcs.
- **RESIZE**: Drag the **Pencil Body** to change the radius.
- **ROTATE**: Drag the **Metal Legs** to rotate the compass without drawing.
- **MOVE**: Drag the **Hinge (Top)** or **Needle Tip** to move the entire tool.

## Initialization
- **Upright Start**: The compass loads in an upright (vertical) position by default.

## Verification

The implementation has been verified against user-provided screenshots and specific requests:
- The pencil stays straight.
- The right arm joint connects perfectly to the bracket.
- The left leg taper is correctly oriented (Straight Outer, Tapered Inner) with the needle facing outside.
- The hinge is taller and the pencil tip is black.

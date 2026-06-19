# Concept Graph — Stress and Energy

## Assumed prerequisites (outside this module)

- Basic familiarity with the idea that the body uses energy (no prior biology required)
- Willingness to read ~30–40 pages of primary text per node

This domain is not strictly prerequisite-ordered the way mathematics is (§12), but the nodes below have a logical dependency: you cannot reason about allostatic load without understanding what the stress response is, and you cannot evaluate health claims without the full model assembled.

## Nodes

```
01 atp-and-cellular-energy
        ↓
02 stress-response-anatomy
        ↓
03 acute-vs-chronic-stress
        ↓
04 allostatic-load          ← schema-building peak
        ↑
05 cortisol-downstream      (feeds into 04 from the mechanism side)
        ↓
06 evaluating-health-claims (synthesis — pulls from all nodes)
```

## Edge semantics

- `01 → 02`: the stress response mobilizes energy — you need to know what energy is before "mobilizing" it means anything
- `02 → 03`: the same anatomical system produces acute and chronic stress; the distinction requires knowing the system first
- `03 → 04`: allostatic load is what happens when acute stress becomes chronic — it is a quantity that accumulates
- `02/03 → 05`: cortisol's downstream effects are downstream of understanding the stress response anatomy
- `05 → 04`: cortisol's specific effects on other systems are part of what makes allostatic load damaging
- `01–05 → 06`: the synthesis node requires the full model to be functional

## Where fluency vs schema-building lives

This is not a procedural domain — there is no fluency floor to build in the math sense. The analog of fluency here is **terminological automaticity**: being able to read "HPA axis," "cortisol," "allostatic load" without stopping to decode. That is achieved through the source reading, not through drills.

All nodes are therefore schema-heavy. Exercises focus on explanation, connection, and transfer.

## Interleaving opportunities

Once nodes 02–04 are complete, the original article ("Why am I so tired all the time") is a natural interleaving object: read a claim from it, identify which nodes it touches, and evaluate whether the causal chain holds.

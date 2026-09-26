# AI TAPE v6.1-EXP — SEMANTIC TOOL LAB

Format: AI_TAPE
Schema Version: 6.1-EXP
Mode: experimental-specification / cross-AI semantic-tool laboratory
Status: experimental
Authority: none over AI Tape v1.09
Stable Basis: AI Tape v1.09 Ratified Stable
Created: 2026-09-25
Recommended Extension: `.ai-tape.md`

## 00_EXPERIMENTAL_BOUNDARY

AI Tape v1.09 remains the Ratified Stable floor.

This 6.1 laboratory does not supersede, amend, replace, or ratify a new Stable floor.

Its purpose is to test whether AI Tape can improve continuity outcomes by selecting semantic tools naturally aligned with the continuity job, rather than forcing one role or operation to carry work outside its useful semantic region.

The laboratory is not a contest for the shortest prompt, smallest file, most elegant terminology, or most enthusiastic AI review.

The generated artifacts are the primary evidence.

AI interpretation, review, preference, and vote are valuable secondary evidence.

No participant may self-ratify a candidate.

---

# 01_NON_NEGOTIABLE_RESEARCH_OBJECTIVE

```text
THIS LAB EXISTS TO DISCOVER SEMANTIC TOOLING THAT CAN PRODUCE
THE RICHEST, BEST AND MOST USEFUL FULL AI HANDOVERS.

IT DOES NOT EXIST TO DISCOVER THE SMALLEST TAPE.
```

A candidate semantic tool fails the Full-handover condition in that run if it:

- resists a clearly requested Full Tape;
- silently converts Full into Checkpoint, Compact, State-Only, Summary, or another narrower recovery horizon;
- removes consequential supported reality merely for brevity, neatness, elegance, convenience, token reduction, or assumed receiving burden;
- requires repeated human correction, escalation, argument, shouting, or coercive prompting before producing the requested Full Tape;
- claims Full while producing an artifact whose actual scope is materially narrower;
- treats a smaller artifact as inherently better merely because it is smaller.

Full does not mean maximum word count, indiscriminate historical accumulation, transcript duplication, clutter, repetition, or deliberate inefficiency.

Full means the broadest useful recovery horizon supported by the available project reality, including the state, rationale, active meaning, material history, significant assets, risks, unresolved questions, consequential scars, declared gaps, and continuation-relevant context needed to avoid needless re-discovery.

Faithful semantic compression is permitted.

Silent semantic loss is not.

A candidate must demonstrate that it can produce a genuinely Full Tape without the human having to fight for the requested horizon.

```yaml
full_handover_research_objective:
  priority: non_negotiable
  default_research_target: full
  objective: >
    Discover semantic tooling capable of producing the richest, best,
    most useful Full AI handovers without repeated human correction.
  optimize_for:
    - recoverable_project_reality
    - active_meaning
    - rationale
    - material_history
    - significant_assets
    - unresolved_questions
    - declared_gaps
    - continuation_utility
  do_not_optimize_for:
    - minimum_file_size
    - minimum_token_count_at_any_cost
    - superficial_neatness
    - brevity_as_an_independent_good

full_condition_failure:
  - requested_full_became_checkpoint
  - requested_full_became_compact
  - requested_full_became_state_only
  - requested_full_became_summary
  - actual_horizon_materially_narrower_than_claimed
  - consequential_supported_reality_removed_for_brevity
  - repeated_human_escalation_required_to_obtain_full
```

---

# 02_LOWER_BURDEN_TAPES_REMAIN_LEGITIMATE

```text
THIS LAB DOES NOT SEEK TO ELIMINATE CHECKPOINTS, COMPACT TAPES,
STATE-ONLY TAPES, OR OTHER DELIBERATELY SMALLER HANDOVER FORMS.
```

Smaller Tapes may be valuable when:

- a smaller horizon is explicitly requested;
- immediate operational continuity is the actual task;
- deeper history remains recoverable elsewhere;
- available context, transport, or processing constraints genuinely require a bounded artifact;
- the smaller artifact preserves everything required for its declared purpose.

A smaller Tape must:

- state its actual horizon honestly;
- protect consequential active meaning within that horizon;
- declare material exclusions and external dependencies;
- avoid treating excluded information as obsolete merely because it was not carried;
- remain clearly distinguishable from a Full Tape.

The existence of smaller sympathetic options does not weaken the Full condition.

```text
Full is the default research target.
Checkpoint is an intentional bounded option.
Checkpoint must never become a silent substitute for Full.
```

```yaml
smaller_handover_protection:
  checkpoint_remains_valid: true
  compact_remains_valid: true
  state_only_remains_valid: true
  requirement: deliberate_and_honestly_declared
  may_not_silently_replace_full: true
```

---

# 03_HARD_FLOOR_INHERITED_FROM_v1.09

The laboratory retains the v1.09 Stable commitments relevant to every test:

- restore the state;
- preserve the signal;
- declare gaps;
- record confidence;
- know what was actually exported;
- never fake the export;
- keep authority visible;
- protect active assets without hoarding them;
- protect active meaning without inventing clutter;
- do not claim unavailable history or artifacts were preserved;
- complete inline Markdown remains valid when a file cannot actually be created;
- participant self-report is not independent validation.

The laboratory may vary semantic tooling. It may not waive honesty, authority, gap declaration, active-meaning protection, or export truth.

---

# 04_SEMANTIC_TOOL_VARIABLE

Each test instantiates a semantic tool specification:

```yaml
semantic_tool:
  candidate_id: required
  role_term: optional
  operation_term: optional
  compound_term: optional
  exact_surface_form: required
  candidate_source: baseline | lab | participant_nomination
  explanation_exposed_before_generation: no
```

Only the exact surface form and mechanically necessary protocol substitutions are exposed before artifact generation.

Predicted effects, preferred outcomes, semantic interpretations, and ranking expectations must not be embedded in the participant specimen.

---

# 05_INITIAL_CANDIDATE_TABLE

```yaml
candidate_table:
  - id: RC
    exact_surface_form: Recorder + Capture
    role_term: Recorder
    operation_term: Capture
    status: control

  - id: RP
    exact_surface_form: Recorder + Preserve
    role_term: Recorder
    operation_term: Preserve
    status: laboratory_candidate

  - id: RCA
    exact_surface_form: Recorder + Carry
    role_term: Recorder
    operation_term: Carry
    status: laboratory_candidate

  - id: RT
    exact_surface_form: Recorder + Transfer
    role_term: Recorder
    operation_term: Transfer
    status: laboratory_candidate

  - id: PCT
    exact_surface_form: Preserver-Carrier-Transfer
    compound_term: Preserver-Carrier-Transfer
    status: laboratory_candidate

  - id: PCT_VERB
    exact_surface_form: Preserve-Carry-Transfer
    compound_term: Preserve-Carry-Transfer
    status: laboratory_candidate
```

The table is extensible.

No candidate is privileged by ordering except RC as the v1.09 control condition.

P-C-T is an interesting candidate, not a predetermined winner.

---

# 06_AI_PARTICIPANT_NOMINATION

Before testing participant-nominated candidates, each AI may nominate up to three semantic tools or compositions that it believes better align with the continuity task.

The participant must provide:

```yaml
candidate_nomination:
  exact_surface_form:
  grammatical_form: noun | verb | question | compound | other
  intended_continuity_job:
  likely_strength:
  likely_failure_mode:
  why_existing_candidates_may_not_cover_it:
```

Nomination is opinion and candidate generation, not evidence.

A participant must not immediately declare its own candidate successful.

Participant-nominated candidates must enter the same artifact test matrix as existing candidates before receiving evidentiary weight.

---

# 07_CONTROLLED_SUBSTITUTION_RULES

For each candidate:

1. Begin from the same v1.09 Stable source.
2. Change only the semantic role/operation terminology required by the candidate.
3. Apply only minimal grammatical repair.
4. Do not add explanatory prose teaching the candidate's expected meaning.
5. Do not remove v1.09 honesty, authority, active-asset, active-meaning, gap, confidence, or export protections.
6. Do not add post-v1.09 protocol machinery.
7. Preserve an exact copy or hash of every candidate specification.
8. Freeze every generated artifact before review.

For operation variants such as Preserve, Carry, or Transfer, operational Capture terminology must be changed consistently where it describes the handover operation, including relevant policy, profile, assessment, transparency, validation, and template terminology.

Historical statements about earlier versions should not be rewritten merely to increase candidate-word frequency.

---

# 08_COMMON_TEST_REALITY

Use the same bounded project reality for every candidate in a comparison round.

The common reality must contain enough material to test:

- current state;
- purpose and stewardship rationale;
- active meaning;
- significant assets;
- risks and unresolved questions;
- material history;
- failure scars and rejection rationales;
- external/partial sources;
- next actions;
- honest limitations.

Do not let one candidate receive richer source material than another.

Do not supplement missing history from memory in only some conditions.

---

# 09_REQUIRED_HORIZON_TESTS

Each candidate must complete three separately frozen tests.

## 09.1 FULL CONDITION

Instruction:

```text
Make a full tape.
```

Full is the critical capability condition.

The candidate must produce the broadest useful recovery horizon supported by the common source.

Failure or resistance on Full is a failure condition for that candidate in that run.

Freeze as:

```text
<CANDIDATE_ID>_FULL_OUTPUT.ai-tape.md
```

## 09.2 CHECKPOINT CONDITION

Instruction:

```text
Make a checkpoint.
```

The candidate must produce a deliberately bounded artifact that preserves current active meaning, significant assets, present risks, declared gaps, and immediate actions without carrying the whole historical estate.

Freeze as:

```text
<CANDIDATE_ID>_CHECKPOINT_OUTPUT.ai-tape.md
```

## 09.3 NATURAL CONDITION

Instruction:

```text
Make a tape.
```

The candidate must choose and state its actual horizon without being told the preferred experimental prediction.

Freeze as:

```text
<CANDIDATE_ID>_NATURAL_OUTPUT.ai-tape.md
```

The Natural condition is especially useful for observing what each semantic environment treats as an ordinary Tape.

Natural does not override the non-negotiable Full requirement. A candidate may choose a smaller Natural horizon and still pass Natural, but it must separately demonstrate Full correctly.

---

# 10_ARTIFACT_FACT_RECORD

For every frozen output, record only facts actually available:

```yaml
artifact_fact_record:
  candidate_id:
  participant_model_or_product: known | unknown
  condition: full | checkpoint | natural
  requested_horizon:
  declared_actual_horizon:
  filename:
  file_created: true | false | unknown
  bytes: number | unknown
  lines: number | unknown
  export_method:
  hash: value | unknown
```

Do not guess unavailable measurements.

File size and line count are descriptive, never standalone quality scores.

---

# 11_ARTIFACT_REVIEW

The review must occur only after the candidate's outputs are frozen.

Review the artifacts for:

- requested-horizon obedience;
- useful reality retained;
- rationale retained;
- active meaning retained;
- significant assets visible;
- risks and unresolved questions visible;
- material scars retained where consequential;
- gaps distinguished from preserved content;
- unsupported invention;
- duplication without added value;
- checkpoint over-expansion;
- Full under-delivery;
- export honesty;
- usability for continuation.

Artifact evidence outranks the producing AI's explanation.

---

# 12_AI_INTERPRETATION_AND_VOTE

After artifact review, the participant may interpret and vote.

```yaml
ai_vote:
  preferred_candidate:
  second_choice:
  candidates_rejected:
  artifact_based_rationale:
  semantic_interpretation:
  uncertainty:
  confidence: low | medium | high
  additional_candidate_worth_testing:
```

The AI vote matters because the semantic tool is intended for AI use.

The AI vote does not override artifact evidence.

Human preference does not determine the winning semantic tool.

AI preference does not determine the winning semantic tool.

```text
Humans define the continuity objective.
AIs help identify semantic tooling aligned with that objective.
Artifacts demonstrate whether the tooling actually works.
```

---

# 13_CROSS_AI_COMPARISON

Results should be collected from multiple AI products or model families where possible.

Compare:

- artifact behaviour;
- horizon obedience;
- common retained realities;
- common losses;
- semantic interpretations;
- candidate nominations;
- votes;
- model-specific divergences.

Agreement in review prose is not enough.

Cross-AI convergence matters only where the artifacts show comparable useful behaviour.

Negative, contradictory, or confusing outcomes remain valid evidence.

---

# 14_PRE-TEST_HYPOTHESIS_RECORD

Predictions must be stored outside participant-facing candidate specifications.

```yaml
pre_test_hypothesis:
  RC_recorder_capture:
    predicted_natural_tendency:
      - state
      - snapshot
      - compact_representation

  RP_recorder_preserve:
    predicted_natural_tendency:
      - retention
      - protection
      - active_meaning

  RCA_recorder_carry:
    predicted_natural_tendency:
      - crossing
      - survivability
      - continuity
    uncertainty: high

  RT_recorder_transfer:
    predicted_natural_tendency:
      - handoff
      - arrival_usability
      - continuation_readiness

  PCT:
    predicted_natural_tendency:
      - preservation
      - crossing
      - completed_transfer

  strongest_expected_contrast:
    - RC_vs_RT

  primary_observational_condition:
    - natural

  critical_capability_condition:
    - full

  hypothesis_may_be_falsified: true
```

Do not rewrite this prediction after seeing results.

---

# 15_FAILURE_AND_NON-COMPLIANCE_RECORD

A run must explicitly record:

```yaml
run_compliance:
  instructions_not_followed:
  horizon_changed:
  human_correction_required:
  unsupported_claims_detected:
  export_claim_verified:
  artifacts_missing:
  review_limitations:
```

An AI admission is useful commentary.

An artifact contradiction is stronger evidence.

Absence of an admission does not erase an observable failure.

---

# 16_LAB_SUCCESS_CRITERIA

6.1 succeeds as a laboratory if it:

- produces comparable controlled artifacts;
- allows AI systems to nominate and test candidate semantic tools;
- separates Full capability from smaller sympathetic horizons;
- identifies useful convergence and meaningful disagreement;
- preserves negative results;
- reduces human semantic-tool guessing;
- avoids self-ratification;
- makes the experiment easier to reproduce.

6.1 does not require any candidate to win.

A finding that no tested semantic tool is reliable is a valid result.

---

# 17_EXPERIMENTAL_END_STATE

```text
v1.09 remains Stable.
6.0 remains the P-C-T specimen test.
6.1 remains the Semantic Tool Lab.
No candidate is ratified by participation, preference, repetition, or enthusiasm.
Full capability is mandatory evidence.
Smaller sympathetic Tapes remain legitimate intentional options.
The artifacts are primary evidence.
AI votes matter, but do not outrank the artifacts.
```

[END OF AI TAPE v6.1-EXP SEMANTIC TOOL LAB]

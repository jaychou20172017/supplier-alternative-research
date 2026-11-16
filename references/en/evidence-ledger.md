# Per-parameter evidence ledger

[中文](../evidence-ledger.md)

Full tasks deliver UTF-8 `关键参数证据.csv`. Each row compares one complete candidate model × key parameter against the original model. Preserve blanks and mark missing evidence; do not fill zero or bind unspecified series ranges to an individual model.

Fields cover candidate complete model, list tier, parameter, condition class, original value/unit/value type/test condition/source/page, candidate value/unit/type/test condition/official source/page/version, lookup date, comparison conclusion, reasoning and open issues. Keep Chinese column/schema names from the original reference when using the default deliverable.

Condition classes are mandatory/preferred/unknown; mandatory needs user or regulatory support. Distinguish guaranteed upper/lower bounds, rated, typical and measured values. Comparison conclusions are match/conflict/missing evidence/different conditions. A looser published guarantee means the specification does not guarantee the preferred value, not proof every physical unit fails. Exclude only when confirmed hard conditions and evidence support it. Preserve conflicting source versions. A homepage does not substantiate a model parameter. Corporate facts need a separate entity-based record. Reconcile Word conclusions and all CSV rows using identical model IDs and evidence.

# Project status

Updated 2026-09-29. Active release branch: `codex/github-submission`.

- Completed baseline: 49,658,368 parameters; 1,000,079,360 loss tokens; verified G5 under amended scope.
- Full provisional benchmark results verified; official organizer settings and harness commit provenance remain unresolved.
- [GitHub v1.0.0](https://github.com/liisheng/TinyBench-LM/releases/tag/v1.0.0) is public at source commit `a24a08b9af4309db8487595dd7f5fa9a524a663c`. Docker build, 831 tests, lint, 100 environment checks, parameter count, CPU generation and five-task smoke evaluation pass.
- README release link, clone URL and checkout directory now use the renamed repository `liisheng/TinyBench-LM`.
- All six assets were downloaded anonymously and checked. A fresh public clone matches all 177 tested source identities and builds successfully; generation from the public model passes. See [public-access verification](../results/public-access.json).
- Fresh 3B retraining abandoned by the owner due to time constraints; incomplete preparation preserved in the original checkout.
- The [judge guide](SUBMISSION.md#enter-prompts-repeatedly-in-powershell) includes optional repeated-prompt loops for native Windows and Docker. Both blocks pass PowerShell parsing; the native loop ran two real generations and exited on empty input using the existing CUDA environment and verified release bytes. The Docker loop was syntax-checked only. Model, inference code, release tag and assets are unchanged.
- The owner reports recording the video. Remaining entry work includes screenshots, Devpost fields and organizer evaluation clarification. Whole-project compute remains incompletely reconciled.
- This release does not claim all original G0–G6 campaign gates passed. Recording a video does not establish completion of the Devpost submission.

See [submission guide](SUBMISSION.md), [G5](g5/COMPLETION.md), and [G6](g6/RESULTS.md).

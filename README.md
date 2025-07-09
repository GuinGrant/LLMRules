# LLM_Rules
trained LLM generating IDS and firewall rules
Under the "test"folder, "Conversation_xLLM_xRules.txt" is the test of LLM prompt:output

"Training_LLM.ipynb" is to train LLM
"Trained_LLM_test.ipynb" is to test trained LLM
"Original_test.ipynb" can test the original model

All compiled in Google Colab, with A100 GPU.

nftables_training_1000.jsonl and Snort_training_300.jsonl are training data in alpaca format, for LoRA fine-tune.

prompt_snort_rule.jsonl is prompt/output format, for prefix and prompt fine-tune.

Comparing ASR models for Russian & English & Ru+En own recorded samples.

I randomly recorded 6 samples for each ru, en, mix (mostly outside, somehow noisy). Yes, I didn't upload them all here, don't see a reason for that tbh. Then using: (1OpenAI Whisper (v3) & Whisper-Turbo & Faster-Whisper (v3),  I evaluated: WER & CER & Latency, you may see the results on /notebooks/ipynb_to_pdf.pdf, where I saved my notebook on colab with outputs (I couldn't do it directly, sad).

Overall key findings for me:
- Whisper-v3 achieved the best overall accuracy (lowest WER).
- Mix sentences significantly degrades performance...
- For some reason, models performed well for Russian, but not so well for English, lol why??
- Whisper-Turbo was so fast, but so Nonstable tbh.

Next time, please try to focus on MIXing languages (how does it work? why model is translating ???).

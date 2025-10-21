# RecoveryCompanion

## Summary
RecoveryCompanion is an idea for a supportive AI assistant designed for people in recovery from addiction. The assistant analyzes short daily reflections and gently helps the user recognize emotions, challenge harmful beliefs, and practice acceptance-focused coping. It aims to provide realistic, compassionate guidance — not false optimism, harsh criticism, or avoidance — so users can live with genuine emotions and face life as it is.

## Background
Many people in recovery face intense emotions, guilt, and fear of the future, which can increase relapse risk. While therapy and peer support are ideal, many cannot access help 24/7. RecoveryCompanion acts as a low-threshold digital friend that provides daily emotional support, realistic encouragement, and reflections to help maintain motivation and acceptance between meetings or therapy sessions.

## What the AI does
- Collects short daily inputs: simple mood tags (e.g., anxious, calm, hopeful) and 1–3 sentence reflections.  
- Uses lightweight natural language processing to detect emotional tone and cognitive distortions (like “I’ll never change”).  
- Suggests short, evidence-based coping exercises such as grounding, mindful breathing, or acceptance reminders.  
- Sends gentle motivational messages when risk signals appear (e.g., repeated cravings or hopelessness).  
- Keeps a private progress log showing emotion trends and small victories over time.

## Data sources
- Synthetic anonymized reflections for prototyping.  
- Public open-source emotion datasets (licensed for research use).  
- Optional anonymized user data (only with consent and full privacy protection).

## Methods
- Preprocessing: tokenization and sentiment lexicon lookup.  
- Emotion classifier: simple logistic regression or small neural network.  
- Belief detector: keyword templates for common cognitive distortions.  
- Rule-based response generator combining emotional label + short coping advice.  
- Privacy-focused local storage or encrypted cloud sync.

## Expected outcome
A minimal prototype that:
- Correctly detects basic emotional states.  
- Flags risk combinations like “hopelessness + craving”.  
- Suggests non-judgmental, practical actions to increase emotional awareness and self-regulation.

## Evaluation
- Usability testing with volunteers (with informed consent).  
- Metrics: user satisfaction, engagement (daily use), emotional clarity improvement.  
- Model metrics: classification precision/recall on test data.

## Ethics and safety
- **Privacy-first:** all data encrypted, anonymized, and user-controlled.  
- **Clear disclaimers:** not a replacement for medical or therapeutic help.  
- **Safe language:** never promotes avoidance, guilt, or self-harm.  
- **Human-in-the-loop:** suggests contacting real help when detecting serious distress.  
- **Transparency:** all model limits and data sources publicly explained.

## Implementation plan
1. Create a web or mobile prototype for daily mood input.  
2. Train a lightweight emotion classifier using open datasets.  
3. Build rule-based coping suggestion engine.  
4. Pilot test, gather feedback, and refine tone and privacy design.

## License & acknowledgements
This project idea was created as part of the **Building AI** course by the **University of Helsinki** and **MinnaLearn**.  
All rights reserved by the author — Hamed Najafi.  
Repository: [https://github.com/auraiglobal-design/my-building-ai-project](https://github.com/auraiglobal-design/my-building-ai-project)

(https://github.com/auraiglobal-design/my-building-ai-project)

---

Created with love to support real recovery through emotional awareness and acceptance. 💙

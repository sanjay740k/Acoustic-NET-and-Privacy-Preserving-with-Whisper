# Acoustic-NET-and-Privacy-Preserving-with-Whisper
Acoustic Named Entity Tagging and Privacy Preserving with Whisper for English and Hindi





![Flowchart](/assets/net_privacy_preserving_flowchart2.jpg)



Example:
Input Audio
{Path}/filename.wav

Transcription (For reference)
अमन भोपाल में रहता है

Outputs:
Enhancing Mode:
<per> अमन <end> <loc> भोपाल <end> में रहता है


Privacy Preserving Mode:
Text Modelity:
All Category
***** ***** में रहता है
LOC Category
<per> अमन <end> ***** में रहता है
PER Category
***** <loc> भोपाल <end> में रहता है




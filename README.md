# Phone_call_line_holder
Waiting for the line with the possibility that real agent come in any moment, but expectation time is very long pissed me off. Got to find a way to solve this problem so I can work on something else while waiting for the line

[Phone call Audio Input]
|
|
[Phone call Chunking] 
|
|
[Preprocessing audio]
|
|
[torch YAMNET classfy the text]
|
|
[Decision Logic: speech & music]
|
|   A if music on waiting state
|   B if speech continue
[base on 10 sec time interval group audio chunk and apply PolyAI/minds14 to obtain transcript]
|
|
[Identify key term within the transcript] ex: "Hi this is...; or agent..."
|
|   A: if key term identify sent alert to other system
|   B: if nothing find continue check utile the audio chunk end.


require:
torch
transformer models.



5 hrs? Maybe?
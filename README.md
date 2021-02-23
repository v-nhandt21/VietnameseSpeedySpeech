## SPEEDYSPEECH MODEL WITH NORMALIZATION FOR FASTER VIETNAMESE SPEECH SYNTHESIS

#### VNUHCM-US_CONF_2020

End to end speech synthesis models have shown better results than traditional methods in terms of intelligence and spontaneity in recent years. However, these network models require a lot of data and training time, and the inference process consumes a lot of GPU resources. With the innovative experiments of SpeedySpeech, the speech synthesis time is shortened and the inference process has ability to run in real-time on the CPU. Authors apply this model for Vietnamese by standardizing the input, replace it with suitable Vietnamese phonemes, improve the embedding layer and the results showed that SpeedySpeech ‘s performance is asymptotic to the Tacotron2 model with significantly shorter training time. Training SpeedySpeech on Colab only takes 19 hours compared to 240 hours of training time on Tacotron2 and the Mel cepstral distortion (MCD) measurement is 990,69 when evaluated based on 200 sample audio tests.

### Measure of how different two sequences of mel cepstra are

![Alt text](Result.png?raw=true)

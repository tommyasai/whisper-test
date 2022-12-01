# Performance Test

# Testing Environment

- Macbook Air
- Chip: M1 (8 core)
- Memory: 16GB

# Result

### Sample: [https://changelog.com/podcast/429](https://changelog.com/podcast/429)

107 min - 102MB

| Model | time to transcript(TTT) | TTT / min | Accuracy | Note |
| --- | --- | --- | --- | --- |
| tiny.en | 18min | 5.94 | ◎ |  |
| base.en | 135min | 0.79 | ◎ |  |
| small.en | 37min | 2.9 | ◎ |  |
| medium.en | 6h 57min | 0.25 | ◎ |  |
| tiny | 20min
94min - without —language specified | 5.35 | ◎ |  |

Ref: [Available Models](https://github.com/openai/whisper/blob/02aa851a49/README.md#available-models-and-languages)
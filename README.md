# EEG-Project

🧠 EEG-to-Text Translation using Transformers
وەرگێڕانی شەپۆلەکانی مێشک بۆ دەق بە بەکارهێنانی مۆدێلی تانسفۆرمەر
📝 Project Overview (کورتی پڕۆژەکە)
This project is a foundational implementation of a Brain-Computer Interface (BCI) system. It demonstrates how electrical brain signals (EEG) can be translated into human language using Deep Learning architectures, specifically Transformers.

ئەم پڕۆژەیە وەک سەرەتایەک بۆ دروستکردنی سیستەمی پەیوەندی نێوان مێشک و کۆمپیوتەر کار دەکات. نیشانی دەدات چۆن ئاماژە کارەباییەکانی مێشک دەکرێن بە دەق و زمان بە بەکارهێنانی ژیریی دەستکرد.

🚀 Key Features (خاڵە سەرەکییەکان)
Synthetic EEG Generation: Simulates brain waves for different words (e.g., "Water" and "Bread").
Transformer Architecture: Uses self-attention mechanisms to understand temporal patterns in brain signals.
Noise Robustness: Evaluates model performance under simulated biological noise (as discussed in recent Scientific Reports studies).
دروستکردنی شەپۆلی دەستکرد: لاساییکردنەوەی شەپۆلی مێشک بۆ وشەی جیاواز.
پێکهاتەی ترانسفۆرمەر: بەکارهێنانی میکانیزمی "سەرنجدان" بۆ تێگەیشتن لە شەپۆلەکان.
بەرگری بەرامبەر ژاوەژاو: تاقیکردنەوەی مۆدێلەکە لە بارودۆخی دەنگەدەنگ و تێکچوونی سیگناڵەکاندا.
🛠️ Tools & Technologies (ئامرازەکان)
Python (Core Language)
PyTorch (Deep Learning Framework)
NumPy (Numerical Data Processing)
Matplotlib (Signal Visualization)
Google Colab (Development Environment)
📊 How it Works (چۆن کار دەکات؟)
Input: 8-channel EEG signals are fed into the model as numerical matrices.
Processing: The Transformer encoder identifies specific frequencies and patterns associated with different thoughts.
Output: A Softmax layer calculates the probability of each word in the vocabulary.
١. تێچوو: شەپۆلی ٨ وایەری EEG وەک ماتریکس دەچێتە ناو مۆدێلەکە. ٢. پرۆسێس کردن: مۆدێلەکە ئەو لەرەلەرە تایبەتانە دەدۆزێتەوە کە پەیوەندییان بە بیرکردنەوەی مرۆڤەوە هەیە. ٣. دەرچوو: مۆدێلەکە ئەگەری وشەکان دیاری دەکات و دروسترینیان هەڵدەبژێرێت.

📈 Future Goals (ئامانجەکانی داهاتوو)
[ ] Connect to real-world EEG datasets (like ZuCo).
[ ] Implement multi-word sentence generation.
[ ] Integrate Real-time BCI streaming.

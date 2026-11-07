# Model AI do rozdzielania wokalu (MusicStudio PRO)

`uvr-mdx-kara-v1.onnx` — model **UVR MDX-NET Karaoke** (`UVR_MDXNET_KARA`) zespołu
[Ultimate Vocal Remover](https://github.com/Anjok07/ultimatevocalremovergui) (program na licencji MIT),
z publicznego zbioru modeli UVR (`TRvlvr/model_repo`, wydanie „all_public_uvr_models”).
Plik ONNX z dodanymi metadanymi pochodzi z wydania `source-separation-models` projektu
[sherpa-onnx](https://github.com/k2-fsa/sherpa-onnx) (Apache-2.0).

- rozmiar: 29 704 738 B
- SHA-256: `4e1cddd765cac6a55785cf28938d02b4ca100cf9ad84d9d86ff1118a50fff8fe`

Aplikacja pobiera ten plik raz, przy pierwszym użyciu „Rozdziel → AI”, sprawdza sumę SHA-256
i dalej działa bez internetu. Nagrania nigdy nie opuszczają urządzenia.

Silnik: [ONNX Runtime](https://github.com/microsoft/onnxruntime) (MIT) — `ort/` (WebAssembly, wersja web)
oraz onnxruntime-android w aplikacji.

# link-searcher-models

Link-Searcher 运行期模型资产，通过 GitHub Release 分发。

## models-v1 资产清单

| 资产 | 大小 | 落盘位置 (data_dir/models/...) |
|------|------|------|
| `paddleocr-det.onnx` / `paddleocr-rec.onnx` / `paddleocr-ppocrv5_dict.txt` | ~21MB | `ppocrv5/` |
| `bge-small-model.onnx` / `bge-small-tokenizer.json` | ~95MB | `bge-small-zh-v1.5/` |
| `funasr-encoder_adaptor.int8.onnx` / `funasr-llm.int8.onnx` / `funasr-embedding.int8.onnx` / `funasr-tokenizer.json` | ~960MB | `funasr/` |

镜像优先：应用默认经 ghfast.top 前缀下载，直连 GitHub 作为回退。

# 🏗️ LoongArch Python Package Build CI

[简体中文](./README_zh.md)

This repository automatically builds and maintains **Python (pip) packages** for the **LoongArch (loongarch64)** architecture.

---

## 📦 Supported Build Workflows

| No. | Package | Workflow |
|-----|----------|-----------|
| 1 | MarkupSafe | [MarkupSafe.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/MarkupSafe.yaml) |
| 2 | PyYAML | [PyYAML.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/PyYAML.yaml) |
| 3 | SQLAlchemy | [SQLAlchemy.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/SQLAlchemy.yaml) |
| 4 | aiohttp | [aiohttp.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/aiohttp.yaml) |
| 5 | apache-tvm | [apache-tvm.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/apache-tvm.yaml) |
| 6 | cadquery-vtk | [cadquery-vtk.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/cadquery-vtk.yaml) |
| 7 | cffi | [cffi.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/cffi.yaml) |
| 8 | charset-normalizer | [charset-normalizer.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/charset-normalizer.yaml) |
| 9 | cibuildwheel | [cibuildwheel.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/cibuildwheel.yaml) |
| 10 | cmake | [cmake.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/cmake.yaml) |
| 11 | confluent-kafka | [confluent-kafka.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/confluent-kafka.yaml) |
| 12 | contourpy | [contourpy.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/contourpy.yaml) |
| 13 | crc32c | [crc32c.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/crc32c.yaml) |
| 14 | cryptography | [cryptography.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/cryptography.yaml) |
| 15 | ctranslate2 | [ctranslate2.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/ctranslate2.yaml) |
| 16 | curl-cffi | [curl-cffi.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/curl-cffi.yaml) |
| 17 | cymem | [cymem.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/cymem.yaml) |
| 18 | datrie | [datrie.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/datrie.yaml) |
| 19 | faiss-cpu | [faiss-cpu.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/faiss-cpu.yaml) |
| 20 | gevent | [gevent.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/gevent.yaml) |
| 21 | greenlet | [greenlet.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/greenlet.yaml) |
| 22 | grpcio-tools | [grpcio-tools.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/grpcio-tools.yaml) |
| 23 | grpcio | [grpcio.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/grpcio.yaml) |
| 24 | h5py | [h5py.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/h5py.yaml) |
| 25 | hf-xet | [hf-xet.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/hf-xet.yaml) |
| 26 | jiter | [jiter.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/jiter.yaml) |
| 27 | kiwisolver | [kiwisolver.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/kiwisolver.yaml) |
| 28 | kornia-rs | [kornia-rs.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/kornia-rs.yaml) |
| 29 | lintrunner | [lintrunner.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/lintrunner.yaml) |
| 30 | llama-cpp-python | [llama-cpp-python.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/llama-cpp-python.yaml) |
| 31 | llguidance | [llguidance.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/llguidance.yaml) |
| 32 | llvmlite | [llvmlite.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/llvmlite.yaml) |
| 33 | lxml | [lxml.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/lxml.yaml) |
| 34 | matplotlib | [matplotlib.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/matplotlib.yaml) |
| 35 | maturin | [maturin.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/maturin.yaml) |
| 36 | ml_dtypes | [ml_dtypes.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/ml_dtypes.yaml) |
| 37 | msgpack | [msgpack.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/msgpack.yaml) |
| 38 | nh3 | [nh3.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/nh3.yaml) |
| 39 | ninja | [ninja.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/ninja.yaml) |
| 40 | nlopt | [nlopt.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/nlopt.yaml) |
| 41 | numba | [numba.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/numba.yaml) |
| 42 | numpy | [numpy.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/numpy.yaml) |
| 43 | onnx | [onnx.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/onnx.yaml) |
| 44 | onnxruntime | [onnxruntime.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/onnxruntime.yaml) |
| 45 | opencv-contrib-python-headless | [opencv-contrib-python-headless.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/opencv-contrib-python-headless.yaml) |
| 46 | opencv-contrib-python | [opencv-contrib-python.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/opencv-contrib-python.yaml) |
| 47 | opencv-python-headlees-rolling | [opencv-python-headlees-rolling.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/opencv-python-headlees-rolling.yaml) |
| 48 | opencv-python-headless | [opencv-python-headless.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/opencv-python-headless.yaml) |
| 49 | opencv-python-rolling | [opencv-python-rolling.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/opencv-python-rolling.yaml) |
| 50 | opencv-python | [opencv-python.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/opencv-python.yaml) |
| 51 | optree | [optree.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/optree.yaml) |
| 52 | orjson | [orjson.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/orjson.yaml) |
| 53 | pandas | [pandas.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/pandas.yaml) |
| 54 | patchelf | [patchelf.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/patchelf.yaml) |
| 55 | pillow | [pillow.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/pillow.yaml) |
| 56 | preshed | [preshed.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/preshed.yaml) |
| 57 | primp | [primp.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/primp.yaml) |
| 58 | psycopg-binary | [psycopg-binary.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/psycopg-binary.yaml) |
| 59 | psycopg2-binary | [psycopg2-binary.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/psycopg2-binary.yaml) |
| 60 | pyarrow | [pyarrow.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/pyarrow.yaml) |
| 61 | pybase16384 | [pybase16384.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/pybase16384.yaml) |
| 62 | pydantic-core | [pydantic-core.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/pydantic-core.yaml) |
| 63 | pygit2 | [pygit2.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/pygit2.yaml) |
| 64 | pymupdf | [pymupdf.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/pymupdf.yaml) |
| 65 | pyodbc | [pyodbc.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/pyodbc.yaml) |
| 66 | pypdfium2 | [pypdfium2.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/pypdfium2.yaml) |
| 67 | regex | [regex.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/regex.yaml) |
| 68 | rpds-py | [rpds-py.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/rpds-py.yaml) |
| 69 | ruamel-yaml-clib | [ruamel-yaml-clib.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/ruamel-yaml-clib.yaml) |
| 70 | ruff | [ruff.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/ruff.yaml) |
| 71 | safetensors | [safetensors.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/safetensors.yaml) |
| 72 | scikit-learn | [scikit-learn.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/scikit-learn.yaml) |
| 73 | scipy-openblas-update | [scipy-openblas-update.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/scipy-openblas-update.yaml) |
| 74 | scipy-openblas | [scipy-openblas.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/scipy-openblas.yaml) |
| 75 | scipy | [scipy.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/scipy.yaml) |
| 76 | sentencepiece | [sentencepiece.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/sentencepiece.yaml) |
| 77 | shapely | [shapely.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/shapely.yaml) |
| 78 | soundfile | [soundfile.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/soundfile.yaml) |
| 79 | soxr | [soxr.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/soxr.yaml) |
| 80 | spacy | [spacy.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/spacy.yaml) |
| 81 | srsly | [srsly.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/srsly.yaml) |
| 82 | swig | [swig.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/swig.yaml) |
| 83 | thinc | [thinc.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/thinc.yaml) |
| 84 | tiktoken | [tiktoken.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/tiktoken.yaml) |
| 85 | tokenizers | [tokenizers.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/tokenizers.yaml) |
| 86 | torch | [torch.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/torch.yaml) |
| 87 | torchaudio | [torchaudio.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/torchaudio.yaml) |
| 88 | torchvision | [torchvision.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/torchvision.yaml) |
| 89 | ujson | [ujson.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/ujson.yaml) |
| 90 | uv | [uv.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/uv.yaml) |
| 91 | uvloop | [uvloop.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/uvloop.yaml) |
| 92 | xxhash | [xxhash.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/xxhash.yaml) |
| 93 | zope.interface | [zope.interface.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/zope.interface.yaml) |

_This table is automatically generated by GitHub Actions._

---

## ⚙️ Automation Details

- Each package has a dedicated workflow under `.github/workflows/`.
- This workflow runs **daily** and regenerates README when workflow files change.

---

## 🕒 Last Updated

- UTC Time: `2026-03-18 04:58:32`
- Local Time (Asia/Shanghai): `2026-03-18 12:58:32`

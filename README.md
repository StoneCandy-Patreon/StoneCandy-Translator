<div align="center">

<img src="doc/images/unusual_notice.jpg" alt="StoneCandy">

</div>

<div align="center">

# 📦 StoneCandy 번역기 공식 배포 채널 안내

StoneCandy 번역기의 **공식 배포는 허깅페이스 쪽에서** 하고 있습니다.<br>
매뉴얼 및 다운로드는 아래 주소로 이동해 주세요.

[huggingface.co/spaces/StoneCandy/StoneCandy-Translator](https://huggingface.co/spaces/StoneCandy/StoneCandy-Translator) <a href="https://huggingface.co/spaces/StoneCandy/StoneCandy-Translator"><img src="https://img.shields.io/badge/%EB%B0%94%EB%A1%9C%EA%B0%80%EA%B8%B0-Hugging%20Face-FF9FB9?style=for-the-badge&logo=huggingface&logoColor=white" alt="공식 배포 페이지" height="48" align="absmiddle"></a>

<sub>※ 소스코드가 아직 정리되지 않았습니다.<br>
반드시 허깅페이스를 통해 <b>Release 버전</b>을 받아 이용해 주세요.</sub>

</div>

---

<div align="center">

# StoneCandy 번역기

[![기반](https://img.shields.io/badge/%EA%B8%B0%EB%B0%98-manga--translator--ui-green)](https://github.com/hgmzhn/manga-translator-ui)
[![기반](https://img.shields.io/badge/%EA%B8%B0%EB%B0%98-manga--image--translator-green)](https://github.com/zyddnys/manga-image-translator)
[![모델](https://img.shields.io/badge/%EB%AA%A8%EB%8D%B8-Real--CUGAN-orange)](https://github.com/bilibili/ailab)
[![모델](https://img.shields.io/badge/%EB%AA%A8%EB%8D%B8-MangaJaNai-orange)](https://github.com/the-database/MangaJaNai)
[![모델](https://img.shields.io/badge/%EB%AA%A8%EB%8D%B8-YSG-orange)](https://github.com/lhj5426/YSG)
[![모델](https://img.shields.io/badge/Model-MangaLens%20Bubble%20Segmentation-orange?logo=huggingface)](https://huggingface.co/huyvux3005/manga109-segmentation-bubble)
[![OCR](https://img.shields.io/badge/OCR-PaddleOCR-blue)](https://github.com/PaddlePaddle/PaddleOCR)
[![OCR](https://img.shields.io/badge/OCR-MangaOCR-blue)](https://github.com/kha-white/manga-ocr)
[![OCR](https://img.shields.io/badge/OCR-PaddleOCR--VL--1.5-blue)](https://huggingface.co/PaddlePaddle/PaddleOCR-VL-1.5)
[![라이선스](https://img.shields.io/badge/%EB%9D%BC%EC%9D%B4%EC%84%A0%EC%8A%A4-GPL--3.0-red)](LICENSE.txt)

</div>

만화 이미지 속 글자를 한 번에 번역합니다. 일본 만화, 한국 웹툰, 서양 코믹스는 물론 흑백·컬러 페이지를 모두 인식할 수 있습니다. 텍스트 검출, OCR, 번역, 인페인팅, 식자를 자동으로 처리하며, 텍스트 상자를 조정할 수 있는 시각 편집기가 내장되어 있습니다.


---

## 사용한 오픈소스 및 모델

- [hgmzhn/manga-translator-ui](https://github.com/hgmzhn/manga-translator-ui) - 기반 프로젝트
- [zyddnys/manga-image-translator](https://github.com/zyddnys/manga-image-translator) - 핵심 번역 엔진
- [bilibili/ailab](https://github.com/bilibili/ailab) - Real-CUGAN 초해상도 모델
- [the-database/MangaJaNai](https://github.com/the-database/MangaJaNai) - MangaJaNai / IllustrationJaNai 초해상도 모델
- [lhj5426/YSG](https://github.com/lhj5426/YSG) - 모델 지원
- [huyvux3005/manga109-segmentation-bubble](https://huggingface.co/huyvux3005/manga109-segmentation-bubble) - MangaLens Bubble Segmentation 말풍선 분할 모델
- [PaddleOCR](https://github.com/PaddlePaddle/PaddleOCR) - OCR 모델 지원
- [kha-white/manga-ocr](https://github.com/kha-white/manga-ocr) - MangaOCR 모델 지원
- [NopeNopeGuy/hayai-ocr](https://github.com/NopeNopeGuy/hayai-ocr) - Hayai OCR v2 모델 지원
- [PaddlePaddle/PaddleOCR-VL-1.5](https://huggingface.co/PaddlePaddle/PaddleOCR-VL-1.5) - 공식 PaddleOCR-VL-1.5 모델 페이지

---

## 📝 라이선스

이 프로젝트의 소스 코드는 **GPL-3.0** 라이선스를 사용합니다. ([LICENSE.txt](LICENSE.txt))

### 모델 라이선스 안내

이미지 초해상도에 쓰는 MangaJaNai / IllustrationJaNai 모델 가중치는 **CC BY-NC 4.0**(저작자표시-비영리 4.0 국제) 라이선스이며, 비상업적 용도로만 사용할 수 있습니다.

- **모델 출처**: [MangaJaNai](https://github.com/the-database/MangaJaNai)
- **모델 라이선스**: CC BY-NC 4.0
- **사용 제한**: 비상업적 용도만 허용

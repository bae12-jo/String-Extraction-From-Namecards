# String-Extraction-From-Namecards

### Project
* AI보안 기술개발 인력양성 교육 개인정보 기술개발 트랙 미니챌린지 
* 1번 프로젝트 명함 OCR 판독

### Date
* 21-10-06 ~ 21-10-31 진행

### Evaluation Point
* OCR 판독율이 높은가?
* 자동화 전처리 코드가 안정적으로 결과를 잘 처리해주는가?

### Environment
* Jupyter Notebook
* Tesseract-OCR

### Base Pipeline Sequence
0. Select Images
1. Load Images
2. Show Images
3. To Gray
4. Edge Detection
5. Historam Equalization
6. Line Detection
7. Smoothing
8. Closing
9. Opening
10. Adaptive Thresolding
11. Thresolding by OTSU
12. Sharpening
13. Contour Dectection
14. Vertex Dection
15. Sort Vertex Order
16. Contrast Adjustment
17. Direction Adjustment
18. OCR
19. Show Result


### Exception Handling
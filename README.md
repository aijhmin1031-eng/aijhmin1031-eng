### AI 에이전트로 일하는 방식을 만듭니다

AI 코딩 에이전트(Claude Code·Codex)를 팀처럼 나눠 운영하면서 업무 자동화와 웹 서비스를 혼자 기획·개발·검증합니다. 방사선 분야에서 14년 일했습니다.

I plan, build and verify web tools and workflow automation with AI coding agents, drawing on 14 years in radiation science.

#### 공개 작업

- **[AI:Radi](https://raditech-platform.vercel.app/)**: 방사선 기술사업화 플랫폼
  - 기술자료 16,671건을 5계층 기술지도로 통합
  - Neo4j 지식그래프와 Voyage 임베딩으로 기술 수요와 공급을 매칭
- **[Radiation Lab](https://radiation-lab.com/)**: 설치 없이 브라우저에서 쓰는 방사선 계산 도구 (개인 프로젝트)
  - **[RadCalc](https://radiation-lab.com/)**
    - 선량률·차폐·붕괴·검출한계(MDA)를 계산
    - 공개된 사례 266개와 대조해 [검증](https://radiation-lab.com/calc/validation/)
    - 오픈소스 [radcalc](https://github.com/radiation-lab-dev/radcalc), DOI [10.5281/zenodo.22794265](https://doi.org/10.5281/zenodo.22794265)
  - **[Field Pro](https://pro.radiation-lab.com/)**
    - ISO 4037 X선·감마 기준장을 모델링
    - 오픈소스 [field-pro](https://github.com/radiation-lab-dev/field-pro)
  - **[M-Phreefiteq](https://disposal.radiation-lab.com/)** (beta): PHREEQC 기반 핵종 이동·지화학 모델링
- **[Dotori Tools](https://dotoriecon.com/)**: 파일을 서버에 올리지 않는 무료 브라우저 도구 모음 (개인 프로젝트)
  - 배경 제거, 물체 지우기, 글자 인식(OCR), 자동 자막 AI 모델이 브라우저 안에서 돌아감

#### AI 활용 분야

- **업무 자동화 에이전트**: MCP 서버와 에이전트 스킬로 문서 작성·결재·보고 업무를 자연어 요청으로 처리
- **지식베이스와 RAG**: 여러 에이전트가 자료를 나눠 모으는 수집 파이프라인으로, 출처를 인용해 답하는 LLM 위키를 구축
- **AI 영상 제작**: 대본 → AI 이미지·영상 생성 → AI 음성 → 자막 검사로 이어지는 제작 파이프라인

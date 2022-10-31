## Machine Learning > AI EasyMaker > 콘솔 사용 가이드

## 노트북 

### 노트북 생성 
머신러닝 개발을 위한 필수 패키지가 설치되어 있는 Jupyter 노트북을 생성할 수 있습니다.

1. **노트북 생성**을 클릭합니다.
2. 노트북의 **이미지**를 선택합니다.
    다음의 노트북 상세 정보를 참고하여 생성하려는 노트북의 이미지를 선택합니다.
    - 이미지 이름: 이미지의 이름이 표시됩니다.
    - 코어 타입: 이미지의 CPU, GPU 코어 타입이 표시됩니다.
    - 프레임워크: 이미지에 설치된 프레임워크가 표시됩니다.
    - 프레임워크: 이미지에 설치된 프레임워크의 버전이 표시됩니다.
3. 노트북 이름을 입력합니다.
4. 노트북에 대한 설명을 입력합니다.
5. **노트북 인스턴스 타입**을 클릭하여 노트북 인스턴스의 타입을 선택합니다.
6. 노트북의 부트 스토리지 크기를 지정합니다. 크기는 10GB 단위로, 최대 2,040GB까지 입력할 수 있습니다.
7. 노트북의 데이터 스토리지 크기를 지정합니다. 크기는 10GB 단위로, 최대 2,040GB까지 입력할 수 있습니다.
8. 태그를 추가하려면 **+ 버튼**을 클릭하여 Key-Value 형식으로 태그를 입력합니다. 태그는 최대 10개까지 입력할 수 있습니다.

> **[참고] 노트북 생성 소요 시간**
> 노트북 생성은 몇 분 정도의 시간이 소요될 수 있습니다.<br>
> 최초 리소스(노트북, 학습, 실험, 엔드포인트) 생성 시 서비스 환경 구성을 위해 추가로 몇 분 정도의 시간이 더 소요됩니다.

### 노트북 목록
노트북의 목록을 확인할 수 있습니다. 목록의 노트북(행)을 클릭하면 노트북의 상세 정보를 확인하고 내용을 변경을 할 수 있습니다.
- **이름**: 노트북 이름이 표시됩니다.
- **인스턴스 타입**: 노트북 인스턴스 타입이 표시됩니다.
- **이미지**: 노트북의 이미지가 표시됩니다.
- **상태**: 노트북의 상태가 표시됩니다. 주요 상태는 다음을 참고하시기 바랍니다.
    - TODO:// 노트북 상태 정리 후 재정리 필요.
    - CREATE: 노트북을 생성하는 중입니다. 
    - ACTIVE (HEALTHY): 노트북이 정상적으로 구동 중인 상태입니다.
    - ACTIVE (UNHEALTHY): 노트북 인스턴스에 애플리케이션이 정상적으로 서비스되지 않고 있는 상태입니다. 노트북을 중지 후 시작한 후에도 이 상태가 지속되면 고객센터로 문의해주세요.
- **Jupyter 노트북 열기**: **Jupyter 노트북 열기** 버튼을 클릭하면 브라우저의 새 창으로 노트북을 엽니다.

### 노트북 인스턴스 타입 변경 
생성된 노트북의 인스턴스 타입을 변경할 수 있습니다.

1. 인스턴스 타입을 변경하려는 노트북을 선택합니다.
2. 노트북이 구동 중인 상태(ACTIVE)인 경우, **노트북 중지**을 클릭하여 노트북을 중지합니다.
3. **인스턴스 타입 변경**을 클릭합니다.
4. 변경하려는 인스턴스 타입을 선택하고 확인을 클릭합니다.
    * TODO//: 변경 불가한 인스턴스 타입 정리 필요.

> **[참고] 인스턴스 타입 변경 소요 시간**
> 인스턴스 타입 변경은 몇 분 정도의 시간이 소요될 수 있습니다.


### 노트북 시작과 중지 
구동 중인 노트북을 중지하거나 중지된 노트북 시작합니다. 

1. 목록에서 시작 또는 중지 하려는 노트북을 선택합니다.
2. **노트북 시작** 또는 **노트북 중지**을 클릭합니다. 
3. 요청된 작업은 취소할 수 없으므로 확인 후 **확인**을 클릭합니다.

> **[참고] 노트북 시작과 중지 소요 시간**
> 노트북 시작과 중지는 몇 분 정도의 시간이 소요될 수 있습니다.


### 노트북 삭제 
생성된 노트북을 삭제할 수 있습니다.
1. 목록에서 삭제하려는 노트북을 선택합니다.
2. **노트북 삭제**을 클릭합니다.
3. 요청된 삭제 작업은 취소할 수 없습니다. 삭제 내용을 다시 확인 후 **확인**을 클릭합니다.


## 학습
TODO:// 학습에 대한 간략한 설명 추가 필요.

### 학습 생성 
학습이 수행될 인스턴스와 OS 이미지를 선택하고, 학습하려는 알고리즘 정보와 입력/출력 데이터를 입력하여 학습을 진행합니다.

1. **+ 학습 생성**을 클릭합니다.
2. 학습 생성 정보를 입력하고 **학습 생성**을 클릭합니다.
3. 학습 생성 정보를 확인하고 **확인**을 클릭합니다. 

- **기본 정보**: 학습에 대한 기본 정보와 학습이 포함될 실험을 선택합니다.
    - **학습 이름**: 학습 이름을 입력합니다.
    - **학습 설명**: 설명을 입력합니다.
    - **실험**: 학습이 포함될 실험을 선택합니다. 생성된 실험이 없는 경우 **추가** 버튼을 클릭하여 실험을 생성합니다.
- **알고리즘 정보**: 학습하려는 알고리즘에 대한 정보를 입력합니다.
    - **알고리즘 경로**
        - **NHN Cloud Object Storage**: 알고리즘이 저장된 Object Storage 경로를 입력합니다.
        <br>obs://{Object Storage API 엔드포인트}/{containerName}/{path} 형식으로 디렉터리 경로를 입력합니다.
            - NHN Cloud Object Storage를 이용하는 경우 [부록 > 1. NHN Cloud Object Storage에 AI EasyMaker 시스템 계정 권한 추가](./console-guide//TODO:Link)을 참고하여 권한을 설정해주세요.
        - **NHN Cloud NAS**: 알고리즘이 저장된 NAS 경로를 입력합니다. <br>nas://{nas ip}:/{path} 형식으로 디렉터리 경로를 입력합니다.
    - **엔트리 포인트**
        - 학습을 시작할 알고리즘의 엔트리 포인트 파일명을 작성합니다. 엔트리 포인트 파일은 알고리즘 경로에 작성한 경로에 존재 해야합니다.
    - **하이퍼파라미터**
        - 학습을 위한 파라미터를 추가하려면 **+ 버튼**을 클릭하여 Key-Value 형식으로 파라미터를 입력합니다. 파라미터는 최대 100개까지 입력할 수 있습니다.

- **이미지**: 학습을 실행할 인스턴스의 이미지를 선택합니다.

- **학습 인스턴스 정보**
    - **학습 인스턴스 타입**: 학습을 실행할 인스턴스의 타입을 선택합니다.
    - **학습 인스턴스 수**: 학습을 수행할 인스턴스 수를 입력합니다. 인스턴스 수를 2개 이상 입력하면 학습 실행이 병렬로 진행되어 보다 빠르게 학습을 진행할 수 있습니다.
    - **데이터 스토리지 크기**: 학습을 실행할 인스턴스의 데이터 스토리지 크기를 입력합니다. 학습에 필요한 데이터가 모두 수용될 수 있도록 충분한 크기를 지정하시기 바랍니다. 

- **데이터 정보**
    - **입력 데이터**: 학습을 실행할 데이터 세트를 입력합니다. 데이터 세트는 최대 10개까지 설정할 수 있습니다.
        - 데이터 세트 이름: 데이터 세트 이름을 입력합니다.
        - 데이터 경로: NHN Cloud Object Storage 또는 NHN Cloud NAS의 경로를 입력합니다.
    - **출력 데이터**: 학습의 실행 결과를 저장할 데이터 저장 경로를 선택합니다.
        - NHN Cloud Object Storage 또는 NHN Cloud NAS의 경로를 입력합니다.

- **추가 설정** 
    - **체크 포인트**: 알고리즘이 체크 포인트를 제공하는 경우, 체크 포인트의 저장 경로를 입력합니다.
        - NHN Cloud Object Storage 또는 NHN Cloud NAS의 경로를 입력합니다.
    - **최대 학습 시간**: 학습이 완료될때까지 최대 대기 시간을 지정합니다. 최대 대기 시간이 초과한 학습은 종료 처리됩니다.
    - **로그 관리**: 학습 진행 중 발생하는 로그를 NHN Cloud Log & Crash 서비스에 저장할 수 있습니다. <br>자세한 내용은[2. NHN Cloud Log & Crash Search 서비스 이용 안내 및 로그 확인](./console-guide//TODO:link)을 참고해주세요.
    - **태그**: 태그를 추가하려면 **+ 버튼**을 클릭하여 Key-Value 형식으로 태그를 입력합니다. 태그는 최대 10개까지 입력할 수 있습니다.

### 학습 목록
학습 목록을 확인할 수 있습니다. 학습 목록에서 학습을 클릭하면 학습의 상세 정보를 확인하고, 설명과 태그를 변경을 할 수 있습니다.

- **이름**: 학습 이름이 표시됩니다. 
- **생성일**: 학습의 생성일시가 표시됩니다.
- **학습 시간**: 학습이 진행된 시간이 표시됩니다.
- **상태**: 학습의 상태가 표시됩니다. 주요 상태는 다음을 참고하시기 바랍니다.
    - TODO:// 상태 재정리 필요.
    - RUNNING: 학습이 진행 중인 상태입니다.
    - COMPLETE: 학습이 정상적으로 완료된 상태입니다.
    - FAIL: 학습 진행 중 실패된 상태입니다. 자세한 실패 정보는 로그 관리가 활성화된 경우, Log & Crash Search 로그를 통해 확인할 수 있습니다.
    - STOPPED: 학습이 사용자의 요청으로 중지된 상태입니다.
- **작업**
    - **텐서보드 바로가기**: 학습 통계 정보를 확인할 수 있는 텐서보드가 브라우저 새 창으로 열립니다.
    - **학습 중지**: 진행 중인 학습을 중지할 수 있습니다.
- **하이퍼파라미터**: 목록에서 확인하려는 학습을 선택하면 하단 화면에 상세 정보가 표시됩니다. **하이퍼파라미터** 탭을 클릭하여, 학습 생성 시 설정한 하이퍼파라미터 값을 확인할 수 있습니다.

### 학습 복사 
기존 학습과 동일한 설정으로 학습을 생성할 수 있습니다.

1. 복사하려는 학습을 선택합니다.
2. **학습 복사**을 클릭합니다. 
3. 학습 인스턴스 타입을 제외한 설정이 기존 학습과 동일한 설정으로 학습 생성 화면이 표시됩니다.
4. 변경하려는 설정 정보가 있다면 변경한 후 **학습 생성**을 클릭하여 학습을 생성합니다.

### 학습 > 모델 생성 
완료된 상태의 학습으로 모델을 생성할 수 있습니다.

1. 모델로 생성하려는 학습을 선택합니다.
2. **모델 생성**을 클릭합니다. 완료(COMPLETE) 상태의 학습만 모델로 생성할 수 있습니다. 
3. [모델] 생성 페이지로 이동됩니다. 내용을 확인 후 **모델 생성**을 클릭하여 모델을 생성합니다.

### 학습 삭제 
학습을 삭제할 수 있습니다.

1. 삭제하려는 학습을 선택합니다.
2. **학습 삭제**을 클릭합니다. 학습이 진행 중인 학습은 삭제할 수 없습니다.
3. 요청된 삭제 작업은 취소할 수 없습니다. 삭제 내용을 다시 확인 후 **확인**을 클릭합니다.

> **[참고] 연관된 모델이 존재할 경우 학습 삭제 불가**
> 삭제하려는 학습으로 생성된 모델이 존재하는 경우 학습을 삭제할 수 없습니다. 모델을 먼저 삭제한 후 삭제해주세요.


## 실험 
연관된 학습을 실험으로 그룹화하여 관리 할 수 있습니다.

### 실험 생성 

1. **+ 실험**을 클릭합니다.
2. 실험 이름과 설명을 입력하고 **실험 생성**을 클릭합니다.

> **[참고] 실험 생성 소요 시간**
> 실험 생성은 몇 분 정도의 시간이 소요될 수 있습니다.<br>
> 최초 리소스(노트북, 학습, 실험, 엔드포인트) 생성 시 서비스 환경 구성을 위해 추가로 몇 분 정도의 시간이 더 소요됩니다.

### 실험 목록 
생성된 실험 목록이 표시됩니다. 목록의 실험을 클릭하면 실험의 상세 정보와 연관된 학습 목록을 확인할 수 있습니다.

- **이름**: 실험 이름이 표시됩니다. 
- **생성일**: 실험의 생성일시가 표시됩니다.
- **상태**: 실험의 상태가 표시됩니다. 주요 상태는 다음을 참고하시기 바랍니다.
    - TODO:// 상태 재정리 필요.
    - ACTIVE: 실험이 정상적으로 생성된 상태입니다.
    - FAIL: 실험 생성이 실패된 상태입니다.
- **작업**
    - **텐서보드 바로가기**을 클릭하면 실험에 포함된 학습의 통계 정보를 확인할 수 있는 텐서보드가 브라우저 새 창으로 열립니다.
    - **재시도**: 실험 상태가 생성일 경우, **재시도**를 클릭하여 실험을 복구할 수 있습니다.

### 실험 삭제 
실험을 삭제할 수 있습니다.

1. 삭제하려는 실험을 선택합니다.
2. **실험 삭제**을 클릭합니다. 실험이 생성 중인 상태인 경우 실험을 삭제할 수 없습니다.
3. 요청된 삭제 작업은 취소할 수 없습니다. 삭제 내용을 다시 확인 후 **확인**을 클릭합니다.

> **[참고] 연관된 실험이 존재할 경우 학습 삭제 불가**
> 실험과 연관된 학습이 존재하는 경우 실험을 삭제할 수 없습니다. 먼저 연관된 학습을 삭제한 후 삭제해주세요.<br>
> 연관된 학습은 삭제하려는 실험을 클릭하면 표시되는 하단의 상세화면에서 **[학습]** 탭을 클릭하여 목록을 확인할 수 있습니다.


## 모델 
AI EasyMaker의 학습 결과의 모델 또는 외부의 모델을 아티팩트로 관리할 수 있습니다.

### 모델 생성 

1. **+ 모델 생성**을 클릭합니다.
2. 모델 생성 정보를 입력하고 **모델 생성**을 클릭합니다.
3. 모델 생성 정보를 확인하고 **확인**을 클릭합니다. 

- **기본 정보**: 모델의 기본 정보를 입력합니다.
    - **이름**: 모델 이름을 입력합니다.
        - [주의] 모델의 프레임워크 종류가 Pytorch인 경우, PyTorch 모델 이름과 동일한 모델 이름을 입력해야 합니다.
    - **설명**: 모델 설명을 입력합니다.
- **프레임워크 정보**: 모델의 프레임워크 정보를 입력합니다.
    - **프레임워크**: 모델의 프레임워크를 Tensorflow 또는 Pytorch 중 선택합니다.
    - **프레임워크 버전**: 모델 프레임워크의 버전을 입력합니다.
- **모델 정보**: 모델의 아티팩트가 저장된 저장소를 입력합니다.
    - **NHN Cloud Object Storage**: 모델 아티팩트가 저장된 Object Storage 경로를 입력합니다.
    <br>obs://{Object Storage API 엔드포인트}/{containerName}/{path} 형식으로 디렉터리 경로를 입력합니다.
        - NHN Cloud Object Storage를 이용하는 경우 [부록 > 1. NHN Cloud Object Storage에 AI EasyMaker 시스템 계정 권한 추가](./console-guide//TODO:Link)을 참고하여 반드시 권한을 설정해주세요.
    - **NHN Cloud NAS**: 모델 아티팩트가 저장된 NAS 경로를 입력합니다. <br>nas://{nas ip}:/{path} 형식으로 디렉터리 경로를 입력합니다.
- **추가 설정 > 태그**: 태그를 추가하려면 **+ 버튼**을 클릭하여 Key-Value 형식으로 태그를 입력합니다. 태그는 최대 10개까지 입력할 수 있습니다.

> **[주의] 프레임워크가 Pytorch인 경우, 모델 이름 설정**
> 모델의 프레임워크 종류가 Pytorch인 경우, 모델 생성 시 반드시 PyTorch 모델 이름과 동일한 모델 이름을 입력해야 합니다.


### 모델 목록 
생성된 모델 목록이 표시됩니다. 목록의 모델을 클릭하면 상세 정보를 확인할 수 있습니다.

- **이름**: 모델 이름이 표시됩니다. 
- **생성일**: 모델의 생성일시가 표시됩니다.
- **수정일**: 모델의 수정일시가 표시됩니다. 

### 모델 > 엔드포인트 생성
등록된 모델을 서빙할 수 있도록 엔드포인트를 생성할 수 있습니다. 

1. 엔드포인트로 생성하려는 모델을 목록에서 선택합니다.
2. **엔드포인트 생성**을 클릭합니다.
3. 학습 인스턴스 타입을 제외한 설정이 기존 학습과 동일한 설정으로 학습 생성화면이 표시됩니다.
4. 변경하려는 설정 정보가 있다면 변경 한 후 **학습 생성**을 클릭하여 학습을 생성합니다.


### 모델 삭제 
모델을 삭제할 수 있습니다.

1. 목록에서 삭제하려는 모델을 선택합니다.
2. **모델 삭제**을 클릭합니다.
3. 요청된 삭제 작업은 취소할 수 없습니다. 삭제 내용을 다시 확인 후 **확인**을 클릭합니다.

> **[참고] 연관된 엔드포인트가 존재할 경우 모델 삭제 불가**
> 삭제하려는 모델로 생성된 엔드포인트가 존재하는 경우, 모델을 삭제할 수 없습니다.
> 삭제하려면 먼저 해당 모델로 생성된 엔드포인트를 삭제한 후 모델을 삭제해주세요.


## 엔드포인트 
모델을 서빙(Serving)할 수 있도록 엔드포인트를 생성하고 관리합니다.

### 엔드포인트 생성

1. **+ 엔드포인트 생성**을 클릭합니다.
2. 엔드포인트 생성 정보를 입력하고 **엔드포인트 생성**을 클릭합니다.
3. 엔드포인트 생성 정보를 확인하고 **확인**을 클릭합니다.

- **API Gateway 서비스 활성화**
    - AI EasyMaker 엔드포인트는 NHN Cloud API Gateway 서비스를 통해 API 엔드포인트를 생성하고 API를 관리합니다. 그러므로 엔드포인트 기능을 이용하시려면 API Gateway 서비스를 반드시 활성화해야 합니다.
    - API Gateway 서비스에 대한 자세한 내용과 요금은 다음의 문서를 확인하시기 바랍니다.
        - [API Gateway 서비스 안내](https://docs.toast.com/ko/Data%20&%20Analytics/Log%20&%20Crash%20Search/ko/Overview/)
        - [API Gateway 이용 요금](https://www.toast.com/kr/pricing/by-service?c=Data%20%26%20Analytics&s=Log%20%26%20Crash%20Search)
- **엔드포인트**: 신규 또는 기존 엔드포인트에 스테이지를 추가할지 선택합니다.
    - **신규 엔드포인트로 생성**: 신규 엔드포인트를 생성합니다. API Gateway에 신규 서비스와 기본 스테이지로 엔드포인트가 생성됩니다.
    - **기존 엔드포인트에서 신규 스테이지 추가**: 기존 엔드포인트의 API Gateway의 서비스에 신규 스테이지로 엔드포인트가 생성됩니다. 스테이지를 추가할 기존 엔드포인트를 선택합니다.
- **엔드포인트 이름**: 엔드포인트 이름을 입력합니다. 엔드포인트 이름은 중복될 수 없습니다.
- **설명**: 엔드포인트 설명을 입력합니다.
- **스테이지 이름**: 기존 엔드포인트에서 신규 스테이지 추가하는 경우, 신규 스테이지의 이름을 입력합니다. 스테이지 이름은 중복될 수 없습니다.
- **모델 정보**: 엔드포인트에 배포할 모델 아티팩트의 정보를 입력합니다.
    - **모델**: 엔드포인트에 배포하려는 모델을 선택합니다. 모델을 생성하지 않은 경우 모델을 먼저 생성하시기 바랍니다.
    - **API Gateway 리소스 경로**: 배포되는 모델의 API 리소스 경로를 입력합니다. 예를 들어 `/inference`로 설정한 경우, `POST https://{enpdoint-domain}/inference`로 추론 API를 요청할 수 있습니다.
- **인스턴스 정보**: 모델이 서빙될 인스턴스 정보를 입력합니다.
    - **인스턴스 타입**: 인스턴스 타입을 선택합니다.
    - **인스턴스 개수**: 인스턴스의 구동 수를 입력합니다.
    - **오토스케일러**: 오토스케일러는 리소스 사용량 정책에 따라 노드 수를 자동으로 조정하는 기능입니다. 오토스케일러는 스테이지 단위로 설정됩니다.
        * 사용/사용 안 함: 오토스케일러 사용 여부를 선택합니다. 사용하는 경우 인스턴스 부하에 따라 인스턴스 수가 스케일 인 또는 아웃됩니다.
        * 최소 노드 수: 감축 가능한 최소 노드 수
        * 최대 노드 수: 증설 가능한 최대 노드 수
        * 감축: 노드 감축 활성 여부 설정
        * 리소스 사용량 임계치: 감축의 기준인 리소스 사용량 임계 영역의 기준값
        * 임계 영역 유지 시간(분): 감축 대상이 될 노드의 임계치 이하의 리소스 사용량 유지 시간
        * 증설 후 감축 지연 시간(분): 노드 증설 후 감축 대상 노드로 모니터링하기 시작까지의 지연 시간
- **추가 설정 > 태그**: 태그를 추가하려면 **+ 버튼**을 클릭하여 Key-Value 형식으로 태그를 입력합니다. 태그는 최대 10개까지 입력할 수 있습니다.

> **[참고] 엔드포인트 생성 소요 시간**
> 엔드포인트 생성은 몇 분 정도의 시간이 소요될 수 있습니다.<br>
> 최초 리소스(노트북, 학습, 실험, 엔드포인트) 생성 시 서비스 환경 구성을 위해 추가로 몇 분 정도의 시간이 더 소요됩니다.

> **[참고] 엔드포인트 생성 시 API Gateway 서비스 리소스 제공 제약**
> 신규 엔드포인트 생성을 하면 API Gateway 서비스를 신규 생성합니다.
> 기존 엔드포인트에서 신규 스테이지 추가를 하면 API Gateway 서비스에 신규 스테이지를 생성합니다.
> [API Gateway 서비스 리소스 제공 정책](https://docs.toast.com/ko/TOAST/ko/resource-policy/#api-gateway)의 리소스 제공 정책을 초과한 경우, AI EasyMaker에서의 엔드포인트 생성이 불가할 수 있습니다. 이 경우 API Gateway 서비스 리소스 쿼터를 조정하시기 바랍니다.


### 엔드포인트 목록 
생성된 엔드포인트 목록이 표시됩니다.

- **이름**: 엔드포인트 이름이 표시됩니다.
- **기본 스테이지 URL**: 엔드포인트의 스테이지 중 기본 스테이지의 URL이 표시됩니다.
- **생성일**: 엔드포인트의 생성일시가 표시됩니다.
- **상태**: 엔드포인트의 상태입니다. 주요 상태는 다음을 참고하시기 바랍니다.
    - TODO:// 상태 정리 필요.
- **API Gateway 상태**: 엔드포인트의 기본 스테이지의 API Gateway의 상태 정보가 표시됩니다.
    - TODO:// 상태 정리 필요.


### 엔드포인트 스테이지 생성
기존 엔드포인트에 신규 스테이지 추가합니다. 신규 스테이지를 생성하여 기본 스테이지의 영향 없이 신규 스테이지를 테스트할 수 있습니다.

1. 엔드포인트 목록에서 **엔드포인트 이름**을 클릭합니다.
2. **+ 스테이지 생성**을 클릭합니다.
3. 기존 엔드포인트에서 신규 스테이지 추가가 자동 선택되며, 설정 방법은 엔드포인트 생성 내용과 동일합니다.
4. 요청된 삭제 작업은 취소할 수 없습니다. 삭제 내용을 다시 확인 후 **확인**을 클릭합니다.


### 엔드포인트 스테이지 목록 
엔드포인트 하위에 생성된 스테이지 목록이 표시됩니다. 목록에 스테이지를 선택하면 상세 정보를 확인할 수 있습니다.

* 스테이지 목록 
    - **스테이지 이름**: 스테이지 이름이 표시됩니다.
    - **스테이지 URL**: 모델이 서빙된 API Gateway의 스테이지 URL이 표시됩니다.
    - **스테이지 이름**: 기본 스테이지 여부가 표시됩니다.
    - **생성일**: 생성일시가 표시됩니다.
    - **상태**: 엔드포인트 스테이지의 상태가 표시됩니다. 주요 상태는 다음을 참고하시기 바랍니다.
        - TODO:// 상태 정리 필요
    - **API Gateway 상태**: 엔드포인트 스테이지가 배포된 API Gateway의 스테이지 상태가 표시됩니다.
* 스테이지 상세 정보
    - 스테이지 이름과 설명: 스테이지 이름과 설명이 표시됩니다. 스테이지의 이름은 생성 후 변경이 불가합니다. 설명은 **변경**을 클릭하여 변경할 수 있습니다.
    - 스테이지 엔드포인트 URL: 스테이지에 배포된 모델의 엔드포인트 URL입니다. API 클라이언트는 표시된 URL로 API를 요청할 수 있습니다.
    - API Gateway 설정 보기: AI EasyMaker가 API Gateway 스테이지에 배포한 설정을 확인하려면, **설정 보기**을 클릭합니다.
    - API Gateway 통계 보기: 엔드포인트의 API 통계를 보려면 **통계 보기**를 클릭합니다.
    - 모델 아이디/이름/아티팩트 경로: 스테이지에 배포된 모델의 정보를 표시합니다.
    - 인스턴스 타입: 모델이 서빙되는 엔드포인트 인스턴스의 타입이 표시됩니다.
    - 오토스케일러 : 오토스케일러 사용 여부가 표시됩니다. **변경**을 클릭하여 사용 여부와 오토스케일러 설정을 변경할 수 있습니다.
    - 실행 중인 워크 노드/파드 수: 엔드포인트에서 사용중인 노드와 파드 수가 표시됩니다.

> [주의] AI EasyMaker가 생성한 API Gateway의 설정 변경 시 주의할 점
> 엔드포인트 생성 또는 엔드포인트 스테이지 생성을 하면 AI EasyMaker는 엔드포인트에 대한 API Gateway의 서비스와 스테이지를 생성합니다.
> AI EasyMaker에 의해 생성된 API Gateway 서비스와 스테이지를 API Gateway 서비스 콘솔에서 직접 변경 작업을 할 경우 다음의 주의 사항을 반드시 참고해주세요.
> 1. AI EasyMaker가 생성한 API Gateway 서비스와 스테이지를 삭제하지 않도록 합니다.
> 2. 엔드포인트 생성시 입력한 API Gateway 리소스 경로의 리소스를 삭제하지 않도록 합니다.
> 3. API Gateway의 스테이지 설정에서 API Gateway 리소스 경로에 설정된 '백엔드 엔드포인트 URL 재정의'를 비활성화하거나 URL을 변경하지 않도록합니다.
> 위의 주의 사항 외 다른 설정은 필요에 따라 API Gateway에서 제공하는 기능을 이용할 수 있습니다.
> 자세한 API Gateway 사용에 대한 내용은 [API Gateway 콘솔 가이드](https://docs.toast.com/ko/Application%20Service/API%20Gateway/ko/console-guide/)를 참고해주세요.

> [참고] 스테이지의 API Gateway '배포 실패' 상태인 경우 복구 방법
> 일시적인 문제로 AI EasyMaker 엔드포인트의 스테이지 설정이 API Gateway 스테이지에 배포되지 않은 경우, 배포 실패 상태로 표시됩니다.
> 이 경우, 스테이지 목록에서 스테이지 선택 > 하단 상세 화면의 API Gateway 설정 보기 > '스테이지 배포'를 클릭하여 API Gateway 스테이지를 수동으로 배포할 수 있습니다. 
> 위 가이드로도 배포 상태가 복구되지 않는 경우 고객센터로 문의해주시기를 바랍니다.


### 엔드포인트 기본 스테이지 변경
엔드포인트의 기본 스테이지를 다른 스테이지로 변경할 수 있습니다.
서비스의 순단 없이 엔드포인트의 모델을 변경하려면 AI EasyMaker는 스테이지 기능을 활용하여 모델을 배포하는 것을 권장합니다.

1. 실제 서비스로 운영 중인 스테이지는 기본 스테이지에서 운영합니다.
2. 신규 모델로 교체하는 경우, 기존 엔드포인트에 신규 스테이지를 추가합니다.
3. 신규 스테이지에서 교체된 모델로 엔드포인트 서비스에 문제가 없는지 확인합니다.
4. **기본 스테이지 변경**을 클릭합니다.
5. 기본 스테이지로 변경하는 신규 스테이지를 변경할 스테이지에서 선택합니다.
6. 변경 요청 작업은 취소할 수 없으므로, 삭제 내용을 다시 확인 후 **확인**을 클릭합니다.
7. 변경할 스테이지가 기본 스테이지로 변경되며, 기존 기본 스테이지의 리소스는 자동으로 삭제됩니다.

### 엔드포인트 스테이지 삭제

1. 엔드포인트 목록에서 **엔드포인트 이름**을 클릭하여 엔드포인트 스테이지 목록으로 이동합니다.
2. 엔드포인트 스테이지 목록에서 삭제할 엔드포인트 스테이지를 선택합니다. 기본 스테이지는 삭제할 수 없습니다.
3. **스테이지 삭제**을 클릭합니다.
4. 요청된 삭제 작업은 취소할 수 없습니다. 삭제 내용을 다시 확인 후 **확인**을 클릭합니다.

> **[주의] 엔드포인트 스테이지 삭제 시 API Gateway 서비스의 스테이지 삭제**
> AI EasyMaker의 엔드포인트 스테이지를 삭제하면, 엔드포인트의 스테이지가 배포된 API Gateway 서비스의 스테이지도 삭제됩니다.
> 삭제되는 API Gateway 스테이지에 운영 중인 API가 존재하는 경우, API 호출이 불가해지므로 주의해주시기를 바랍니다.


### 엔드포인트 스테이지의 오토스케일러 변경
엔드포인트 스테이지 설정된 오토스케일러의 사용 여부와 설정을 변경할 수 있습니다.

1. 엔드포인트 목록에서 엔드포인트의 이름을 클릭합니다.
2. 엔드포인트 스테이지 목록에서 오토스케일러 설정을 변경하려는 스테이지를 선택합니다.
3. 하단의 상세 화면에 오토스케일러 옆 **변경**을 클릭합니다.
4. 오토스케일러 설정은 변경한 후 **확인**을 클릭합니다.

> **[참고] 오토스케일러 변경 소요 시간**
> 오토스케일러 설정 변경 작업은 몇 분 정도 소요가 됩니다. 
> 변경 작업이 진행 중인 경우에는 다시 변경할 수 없으므로 작업이 완료된 후 변경해주세요.


### 엔드포인트 삭제 
엔드포인트를 삭제할 수 있습니다.

1. 엔드포인트 목록에서 삭제하려는 엔드포인트를 선택합니다.
2. 엔드포인트 하위에 기본 스테이지를 제외한 스테이지가 존재하는 경우, 엔드포인트를 삭제할 수 없습니다. 먼저 다른 스테이지를 삭제한 후 삭제해주세요.
3. **엔드포인트 삭제**를 클릭합니다.
4. 요청된 삭제 작업은 취소할 수 없습니다. 삭제 내용을 다시 확인 후 **확인**을 클릭합니다.

> **[주의] 엔드포인트 스테이지 삭제 시 API Gateway 서비스의 기본 스테이지 삭제**
> AI EasyMaker의 엔드포인트 스테이지를 삭제하면, 엔드포인트의 스테이지가 배포된 API Gateway 서비스의 기본스테이지도 삭제됩니다.
> 삭제되는 API Gateway 기본 스테이지에 운영 중인 API가 존재하는 경우, API 호출이 불가해지므로 주의해주시기 바랍니다.


## 부록 

### 1. NHN Cloud Object Storage에 AI EasyMaker 시스템 계정 권한 추가
AI EasyMaker 서비스가 사용자의 NHN Cloud Object Stoage에 파일을 읽거나 쓰려면 NHN Cloud Object Storage에 AI EasyMaker 시스템 계정을 권한 추가해야 합니다.

1. **[학습]** 또는 **[모델]** 탭 > **AI EasyMaker 시스템 계정 정보**을 클릭합니다. 
2. EasyMaker 시스템 계정 정보인 **AI EasyMaker 테넌트 ID**와 **AI EasyMaker API 사용자 ID** 를 보관합니다. 
3. NHN Cloud Object Storage 콘솔로 이동합니다. 
4. [특정 프로젝트 또는 특정 사용자에게 읽기/쓰기 허용](https://docs.toast.com/ko/Storage/Object%20Storage/ko/acl-guide/#references) 문서를 참고하여 EasyMaker 시스템 계정의 읽기/쓰기 허용 권한을 추가합니다.

### 2. NHN Cloud Log & Crash Search 서비스 이용 안내 및 로그 조회 방법
EasyMaker서비스에서 발생하는 로그, 이벤트를 NHN Cloud Log & Crash Search 서비스에 저장할 수 있습니다.
Log & Crash Search 서비스에 로그를 저장하려면, Log & Crash 서비스를 활성화해야 하며 별도 이용 요금이 부과됩니다.

- Log & Crash Search 서비스 이용 및 요금 안내 
    - Log & Crash Search 서비스에 대한 자세한 내용과 요금은 다음의 문서를 확인하시기 바랍니다. 
        - [Log & Crash Search 서비스 안내](https://docs.toast.com/ko/Data%20&%20Analytics/Log%20&%20Crash%20Search/ko/Overview/)
        - [Log & Crash Search 이용 요금](https://www.toast.com/kr/pricing/by-service?c=Data%20%26%20Analytics&s=Log%20%26%20Crash%20Search)


- 저장되는 로그 
    - TODO:// 저장되는 로그 정보 정리 (테이블 형태)


- 로그 조회 
    1. Log & Crash Search 서비스 콘솔 페이지로 이동합니다.
    2. Log & Crash Search 서비스에서 logType 필드가 "NNH Cloud-AI EasyMaker"인 로그를 조회합니다.
        * 조회 질의: logType: "NHN Cloud-AI EasyMaker"
    3. Log & Crash Search 서비스의 자세한 이용 방법은 [Log & Crash Search 서비스의 콘솔 가이드](https://docs.toast.com/ko/Data%20&%20Analytics/Log%20&%20Crash%20Search/ko/console-guide/)를 참고해주세요.
# Bouncycastle
Bouncy Castle 은 암호화에 사용되는 API 모음입니다. Java 및 C # 프로그래밍 언어 모두에 대한 API가 포함되어 있습니다.

Bouncy Castle은 두 명의 동료가 서버 측 Java SE 에서 작업하는 작업을 변경할 때마다 일련의 암호화 라이브러리를 다시 작성해야하는 것에 지쳐 있었기 때문에 시작되었습니다. 
개발자 중 한 명이 자바 ME (당시 J2ME) 개발에서 취미로 활동했으며 설계 고려 사항은 J2ME의 Java VM을 포함하여 라이브러리에 가장 많은 범위의 Java VM을 포함시키는 것이 었습니다. 
이 디자인 고려 사항은 Bouncy Castle에 존재하는 아키텍처로 이어졌습니다.
원래 Java API는 테스트 코드 및 J2ME, JCE / JCA 공급자 및 기본 X.509 인증서 생성에 대한 지원을 포함하여 약 27,000 줄의 코드로 구성되었습니다. 이에 비해 1.53 릴리스는 테스트 코드를 포함하여 390,640 줄의 코드로 구성됩니다. 
PKCS # 10, PKCS # 12, CMS, S / MIME , OpenPGP , DTLS , TLS , OCSP , TSP , CMP , CRMF, DVCS , DANE , EST 와 같은 많은 기능을 갖춘 원본 릴리스와 동일한 기능을 지원합니다.  
C # API는 약 145,000 줄의 코드이며 Java API의 대부분을 지원합니다.

#JAVA Provider Framework
java.security
javax.crypto
javax.crypto.spec
javax.crypto.interfaces
That means that the encryption is not done by the JCA, but by the provider.

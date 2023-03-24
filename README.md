#아핀(Affine) 암호:

아핀 암호는 카이사르 암호를 보완한 암호화 기법 중 하나입니다.
암호화 과정에서 입력값을 먼저 공간 내에서 하나의 정수로 매핑합니다.
이후 아핀 함수를 적용하여 암호화를 수행하며, 이때 공간의 크기와 암호화에 사용되는 함수 파라미터는 모두 서로소 관계여야 합니다.


#카이사르(Caesar) 암호:

카이사르 암호는 평문의 각 문자를 알파벳 상에서 고정된 거리만큼 회전시켜 암호화하는 대칭키 방식입니다.
암호화와 복호화에 사용되는 키는 정수 하나이며, 이를 이용해 알파벳 상에서 회전하는 거리를 결정합니다.
간단한 구현과 계산이 가능하지만, 키 공간이 작아 보안성이 낮습니다.


#전치(Transposition) 암호:

전치 암호는 평문을 고정된 길이의 블록으로 나누어 이를 순서대로 배열한 뒤, 특정 규칙에 따라 재배치하여 암호화합니다.
특히, 행렬 형태로 평문을 배열하고 이를 전치하여 암호화하는 방식을 가리켜 행렬 전치 암호(Matrix Transposition Cipher)라고도 합니다.
평문의 길이나 배열 규칙을 다양화하여 보안성을 향상시킬 수 있으며, 기존의 암호화 기법과 함께 사용할 경우 추가적인 보안성을 제공할 수 있습니다.


#비즈네르(Vigenere) 암호:

비즈네르 암호는 카이사르 암호와 유사하지만, 키 값을 랜덤 문자열로 설정하여 평문의 각 문자에 대해 서로 다른 이동 거리를 적용합니다.
암호화 과정에서 평문의 각 문자를 알파벳 상에서 고정된 거리만큼 이동시키는 것이며, 키는 문자열로 구성되어 있습니다.
평문과 암호문의 길이가 같기 때문에 다른 암호화 기법과 함께 사용할 경우 보안성을 향상시킬 수 있습니다. 

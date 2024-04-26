# Detecção de Máscara Facial com Haar Cascade Classifier
Este script em Python foi desenvolvido para detectar máscaras faciais em um conjunto de dados específico. Utiliza a biblioteca OpenCV para processamento de imagem, além de XML para anotações e a biblioteca Matplotlib para visualização.

# Requisitos
Certifique-se de ter as seguintes bibliotecas instaladas:

OpenCV (cv2)
Matplotlib (matplotlib)

# Como usar
Baixe o script Python.
Certifique-se de ter as imagens e seus arquivos de anotação XML em diretórios separados.
Defina as pastas de imagens (images_folder) e anotações (annotations_folder) no script para corresponder aos diretórios em seu sistema.
Execute o script.

# Funcionalidades
- O script embaralha as imagens e processa um número específico delas (definido por num_images_to_process).
- Utiliza um classificador Haar Cascade para detectar rostos nas imagens.
- Renderiza as imagens com retângulos vermelhos delimitando as faces detectadas.
- Exibe os rótulos das classes acima dos retângulos correspondentes.
  
# Exemplo de Uso
Definir pastas de imagens e anotações
images_folder = r'C:\Users\Neri\Downloads\archive (7)\images'
annotations_folder = r'C:\Users\Neri\Downloads\archive (7)\annotations'

Processar as imagens
process_images(images_folder, annotations_folder, num_images_to_process=5)

Este script é útil para visualizar a detecção de máscaras faciais em um conjunto de dados e pode ser adaptado para outros projetos de detecção de objetos.
- Foi utilizado uma base de dados do site Kaggle.com

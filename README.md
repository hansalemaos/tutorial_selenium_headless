### Tutorial (Brazilian Portuguese)

[![YT](https://i.ytimg.com/vi/slmy3bygaSk/maxresdefault.jpg)](https://www.youtube.com/watch?v=slmy3bygaSk)
[https://www.youtube.com/watch?v=slmy3bygaSk]()

Neste vídeo, apresento uma solução simples e eficaz para executar o Selenium em modo headless. Em vez de depender da opção "--headless" fornecida pelo Selenium, desenvolvi uma abordagem chamada "PoorMansHeadless" que garante um funcionamento consistente e confiável.

O código-fonte completo dessa solução está disponível no GitHub, no repositório chamado "PoorMansHeadless". Você pode encontrá-lo no link: https://github.com/hansalemaos/PoorMansHeadless

No vídeo, explico passo a passo como usar o PoorMansHeadless. 

 Primeiro, crio uma instância do driver Chrome usando o undetected_chromedriver. Em seguida, carrego o site do Google usando o método "get". Para capturar uma captura de tela, utilizo o método "get_screenshot_as_png". Obtenho o identificador da janela usando a função "get_hwnd" fornecida pelo FakeHeadless.

Então, inicio o modo headless chamando o método "start_headless_mode" do FakeHeadless, passando o identificador da janela como parâmetro. Nesse método, também é possível definir a largura, altura e a distância da janela em relação à barra de tarefas.

Por fim, crio uma função chamada "screenshot1" que exibe a captura de tela usando o OpenCV e a função "cv2_imshow_single" do pacote cv2imshow. Essa função aceita a imagem convertida para o formato suportado pelo OpenCV e exibe-a em uma janela chamada "sele1". Além disso, ela define a combinação de teclas "ctrl+alt+q" para fechar a janela.

Assista a este vídeo para aprender como utilizar o PoorMansHeadless e executar o Selenium de forma eficiente em modo headless. Espero que esse código seja útil para você e facilite suas tarefas de automação com o Selenium. Se tiver alguma dúvida, deixe um comentário abaixo e ficarei feliz em ajudar.


saturno.parallax
================

Um plugin leve e fácil para criar efeitos parallax com jQuery.

Para usar é muito fácil, tudo que você precisa é de um DIV com altura definida e uma imagem no background dele.
Depois, é só chamar o plugin:

  $('#praia2').saturno({
  velocidade: 10,
  fade: true,
  fade_suavizacao: 1000
  });

Você pode definir a velocidade (que pode ser negativa), se será feito um fadeOut conforme a página rola, e qual a suavização desse fade. Quanto mais suave, menos fade será aplicado.

Exemplo de código funcional:
http://jsfiddle.net/lucasleal/wty3r2L5/

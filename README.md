# Melanoma AI

A plataforma de saúde digital **Melanoma AI** utiliza Inteligência Artificial para auxiliar na triagem e identificação de risco de lesões cutâneas suspeitas por meio de uma abordagem **Multimodal**, ou seja, utiliza a coleta de dados e também a coleta de imagens para a identificação.

---

## Diferenciais do Projeto

Ao contrário de modelos que analisam apenas uma imagem isolada, o Melanoma AI utiliza:
- **Late Fusion (Fusão Tardia):** Integração das informações obtidas por meio das imagens e os dados coletados.
- **Estratégia do Patinho Feio:** O sistema compara a lesão suspeita com outras pintas do próprio paciente para identificar anomalias contextuais.
- **Abordagem Multimodal:** 8 dados clínicos + 2 vetores referentes as 3 imagens necessárias.

---

## Parâmetros

### 1. Dados Clínicos

1.  **Idade:** Fator de risco cumulativo.
2.  **Sexo Biológico:** Influencia a incidência e localização comum de lesões.
3.  **Histórico Pessoal:** Se o paciente já teve câncer de pele anteriormente.
3.  **Histórico Familiar:** Predisposição genética.
4.  **Localização Anatômica:** Região do corpo onde a mancha está (ex: dorso, membros, face).
5.  **Diâmetro:** Medida em milímetros (atenção especial para lesões > 6mm).
6.  **Evolução:** Relato de mudanças recentes em cor, tamanho ou forma.
7.  **Histórico de Queimaduras:** Registro de episódios graves de queimadura solar com bolhas.

### 2. Imagens

O sistema solicita três entradas de imagem:
1.  **Lesão Suspeita:** A imagem principal para análise detalhada de bordas, cores e simetria.
2.  **Pintas de Controle (Patinho Feio):** Duas imagens de outras pintas benignas do paciente para que a IA entenda o "padrão normal" da pele daquela pessoa e identifique se a lesão suspeita é uma anomalia (outlier).

---

## Aviso Legal (Disclaimer)
Este software é uma ferramenta de **triagem experimental**. 
1. **Não substitui o diagnóstico médico.**
2. Os resultados são probabilidades baseadas em dados estatísticos.
3. Sempre consulte um dermatologista para avaliações clínicas.

---

## Autores
- **Mateus Bueno** - [GitHub](https://github.com/PHOBOSSPEC)
- **Filipe Macarini** - [GitHub](https://github.com/filipemacarini)

---

*Este projeto foi desenvolvido com fins acadêmicos e de pesquisa em IA voltada à saúde.*
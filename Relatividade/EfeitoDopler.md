**Derivação da Equação 37.5.1 (Efeito Doppler Relativístico)**

Considere uma fonte de luz em repouso no referencial \( S' \), que se move com velocidade \( v \) ao longo do eixo \( x \) em relação ao referencial \( S \). Queremos relacionar a frequência \( f \) medida em \( S \) com a frequência própria \( f_0 \) emitida em \( S' \).

---

### **Passo 1: Transformações de Lorentz para Tempo e Espaço**
As transformações de Lorentz entre \( S' \) e \( S \) são:
\[
\Delta t = \gamma \left( \Delta t' + \frac{v \Delta x'}{c^2} \right),
\]
\[
\Delta x = \gamma \left( \Delta x' + v \Delta t' \right),
\]
onde \( \gamma = \frac{1}{\sqrt{1 - v^2/c^2}} \).

---

### **Passo 2: Relação entre Períodos**
A luz emitida pela fonte em \( S' \) tem período próprio \( T_0 = \frac{1}{f_0} \). Dois eventos consecutivos (como a emissão de duas cristas de onda) são separados por:
\[
\Delta t' = T_0, \quad \Delta x' = 0 \quad (\text{fonte está em repouso em } S').
\]
Substituindo em \( \Delta t \):
\[
\Delta t = \gamma \Delta t' = \gamma T_0.
\]
O período medido em \( S \) é \( T = \Delta t \), então:
\[
T = \gamma T_0.
\]

---

### **Passo 3: Efeito Doppler devido ao Movimento Relativo**
Se a fonte **se afasta** de \( S \), cada crista de onda percorre uma distância adicional \( v T \) entre emissões. O tempo adicional para cada crista alcançar o observador em \( S \) é:
\[
\Delta t_{\text{extra}} = \frac{v T}{c}.
\]
O período total medido \( T_{\text{obs}} \) é:
\[
T_{\text{obs}} = T + \frac{v T}{c} = T \left(1 + \frac{v}{c}\right).
\]
Substituindo \( T = \gamma T_0 \):
\[
T_{\text{obs}} = \gamma T_0 \left(1 + \frac{v}{c}\right).
\]

---

### **Passo 4: Frequência Observada**
A frequência medida em \( S \) é \( f = \frac{1}{T_{\text{obs}}} \):
\[
f = \frac{1}{\gamma T_0 \left(1 + \frac{v}{c}\right)}.
\]
Como \( f_0 = \frac{1}{T_0} \):
\[
f = \frac{f_0}{\gamma \left(1 + \frac{v}{c}\right)}.
\]

---

### **Passo 5: Simplificação usando \( \gamma \)**
Substitua \( \gamma = \frac{1}{\sqrt{1 - v^2/c^2}} \):
\[
f = f_0 \sqrt{1 - \frac{v^2}{c^2}} \left( \frac{1}{1 + \frac{v}{c}} \right).
\]
Simplifique a expressão:
\[
f = f_0 \sqrt{\frac{1 - \frac{v}{c}}{1 + \frac{v}{c}}}.
\]
Definindo \( \beta = \frac{v}{c} \), obtemos:
\[
f = f_0 \sqrt{\frac{1 - \beta}{1 + \beta}}. \quad \text{(Equação 37.5.1)}
\]

---

### **Casos Especiais**
1. **Fonte se aproximando (\( v < 0 \)):**  
   \[
   f = f_0 \sqrt{\frac{1 + |\beta|}{1 - |\beta|}} \quad \text{(blueshift)}.
   \]

2. **Velocidades baixas (\( \beta \ll 1 \)):**  
   Expanda em série de Taylor:
   \[
   f \approx f_0 \left(1 - \beta \right) \quad \text{(aproximação clássica)}.
   \]

---

**Conclusão:**  
A Equação 37.5.1 descreve o efeito Doppler relativístico para luz, incorporando dilatação temporal e movimento relativo. Ela é fundamental para interpretar desvios espectrais em astronomia e aplicações como radares. 

\[
\boxed{f = f_0 \sqrt{\frac{1 - \beta}{1 + \beta}}}
\]

### **Efeito Doppler Transversal**

Até agora, discutimos o efeito Doppler, tanto neste capítulo como no Capítulo 17, em situações nas quais a fonte e o detector se movem **na mesma direção** ou **em direções opostas**.  

A **Figura 37.5.1** mostra um arranjo diferente, no qual uma **fonte \( S \)** passa ao lado de um **detector \( D \)**. No instante em que \( S \) está passando pelo **ponto \( P \)**, a **velocidade de \( S \) é perpendicular** à reta que liga \( S \) a \( D \), o que significa que a **fonte não está se aproximando nem se afastando de \( D \)**.  

- Se a fonte emitir **ondas sonoras** de frequência \( f_0 \), as ondas emitidas no **ponto \( P \)** serão detectadas por \( D \) com a **mesma frequência** (ou seja, **sem efeito Doppler**).  
- Entretanto, se a fonte emitir **ondas luminosas**, haverá um **efeito Doppler**, conhecido como **efeito Doppler transversal**.  

Nessa situação, a frequência detectada no ponto \( D \) da luz emitida quando a fonte estava passando pelo ponto \( P \) será dada por:

\[
f = f_0 \sqrt{1 - \beta^2} \quad (\text{efeito Doppler transversal}) \quad (37.5.7)
\]

Para **baixas velocidades** (\( \beta \ll 1 \)), a Eq. (37.5.7) pode ser expandida em uma série de potências de \( \beta \) e expressa na forma aproximada:

\[
f = f_0 (1 - \frac{1}{2} \beta^2) \quad (\text{baixas velocidades}) \quad (37.5.8)
\]

- O **primeiro termo** dessa equação é o **resultado esperado** para ondas sonoras.
- O **efeito relativístico** para fontes e detectores de luz que se movem em **baixa velocidade** aparece na forma de um termo **proporcional a \( \beta^2 \)**.

#### **Aplicação do efeito Doppler transversal**
Graças ao efeito Doppler transversal, um **radar de polícia poderia, em princípio, medir a velocidade de um carro**, mesmo que o **radar estivesse apontado perpendicularmente** à trajetória do carro.  

Entretanto:
- Como \( \beta \) é **pequeno**, o efeito Doppler transversal **é proporcional a \( \beta^2 \)**.
- No efeito Doppler normal, a variação da frequência é **proporcional a \( \beta \)**.
- Isso significa que **o efeito Doppler transversal é muito pequeno** e **não pode ser medido pelo radar da polícia**.

Por essa razão, **os policiais procuram alinhar o radar com a trajetória do carro**, para obter uma medição precisa da velocidade. **Qualquer desalinhamento favorece o motorista**, pois **a velocidade medida será menor que a velocidade real**.

#### **Efeito Doppler Transversal e Dilatação do Tempo**
O efeito Doppler transversal **é uma consequência da dilatação relativística do tempo**.  

Se escrevermos a Eq. (37.5.7) em termos do **período** \( T = 1/f \) das oscilações da luz, obtemos:

\[
T = \frac{T_0}{\sqrt{1 - \beta^2}} = \gamma T_0. \quad (37.5.9)
\]

onde \( T_0 (= 1/f_0) \) é o **período próprio da fonte**.

Na verdade, tanto a **Eq. (37.1.9)** quanto a **Eq. (37.5.9)** **são expressões da lei da dilatação do tempo**, pois o período é um intervalo de tempo.

---

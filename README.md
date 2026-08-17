The following action was requested:
View contents of file /server.ts from lines 1 to 150The action produced the following result:
File Path: /server.ts
Total Lines: 239
Total Bytes: 11036
Showing lines 1 to 150
The following code has been modified to include a line number before every line, in the format: <line_number>: <original_line>. Please note that any changes targeting the original code should remove the line number, colon, and leading space.
1:
The above content does NOT show the entire file contents. If you need to view any lines of the file which were not shown to complete your task, call this tool again to view those lines.The following action was requested:
View contents of file /server.ts from lines 145 to 239The action produced the following result:
File Path: /server.ts
Total Lines: 239
Total Bytes: 11036
Showing lines 145 to 239
The following code has been modified to include a line number before every line, in the format: <line_number>: <original_line>. Please note that any changes targeting the original code should remove the line number, colon, and leading space.
145:
The above content shows the entire, complete file contents of the requested file.The following action was requested:
Create file /src/utils/fallbackGenerator.tsThe action produced the following result:
Successfully created file /src/utils/fallbackGenerator.ts with content:
import { TrendingProduct, ProductStrategy } from "../types";
export function generateDynamicFallbackStrategy(
product: Partial<TrendingProduct>,
customPrompt?: string
): ProductStrategy {
const name = product.name || "Produto em Alta no TikTok Shop";
const category = product.category || "E-commerce & Utilidades";
const niche = product.niche || category;
const price = product.averagePriceBrl || 79.90;
const anchorPrice = (price * 1.5).toFixed(2);
const tiktokPrice = price.toFixed(2);
const viralFactor = product.viralFactor || "Demonstração visual instantânea e alto impacto de antes/depois";
return {
executiveSummary: O produto '${name}' na categoria de ${category} aproveita uma das dores mais fortes do consumidor do TikTok: praticidade visual instantânea aliada a excelente custo-benefício. Ao trabalhar um formato de conteúdo nativo focado em demonstração sem filtro, o produto gera pico de desejo imediato com forte conversão na sacolinha amarela. ${customPrompt ?Foco adicional solicitado: ${customPrompt}: ""},
viralVideoHooks: [
{
hookType: "Problema vs Solução Cotidiana",
spokenHook: Se você ainda sofre com isso no seu dia a dia, precisa ver o que essa solução faz em 5 segundos!,
visualAction: Mostrar o problema frustrante em close dramático e, em seguida, acionar o ${name} resolvendo instantaneamente.,
onScreenText: ⚠️ PARE DE SOFRER COM ISSO AGORA!
},
{
hookType: "Curiosidade Chocante",
spokenHook: Eu não acreditava que esse achadinho do TikTok Shop funcionava até fazer esse teste na prática...,
visualAction: Apresentar o produto em ação extrema com iluminação limpa e zoom rápido no resultado final.,
onScreenText: TESTEI O PRODUTO VIRAL DO TIKTOK! 😱
},
{
hookType: "Antes e Depois Visual",
spokenHook: Dá uma olhada nisso aqui antes... e olha agora depois de usar em menos de 1 minuto!,
visualAction: Transição rápida com estalo de dedos ou corte de cena mostrando o contraste brutal de transformação.,
onScreenText: O RESULTADO É SURREAL! ✨🔥
},
{
hookType: "Controvérsia / Alerta de Economia",
spokenHook: Por que ninguém me contou antes que dava pra resolver isso pagando menos de R$ ${tiktokPrice}?,
visualAction: Segurar o produto com sorriso e apontar diretamente para a sacolinha amarela com o preço especial.,
onScreenText: MENOS DE R$ ${tiktokPrice}? NUNCA MAIS GASTO CARO! 💸
},
{
hookType: "Segredo das Gringas / Tendência",
spokenHook: Esse é o motivo desse item estar esgotando em todos os países e agora chegou no Brasil!,
visualAction: Unboxing rápido tirando o produto da embalagem e mostrando a qualidade do acabamento.,
onScreenText: ESGOTOU LÁ FORA E CHEGOU NO BRASIL 🇧🇷✨
}
],
videoScripts: [
{
title: "Roteiro UGC 'Demonstração Prática & Conversão na Sacolinha'",
duration: "30 a 35 segundos",
objective: "Conversão direta por desejo imediato e quebra de objeções",
audioTrackSuggestion: "Trilha pop energética ou batida lo-fi ritmada com efeitos sonoros nítidos",
storyboard: [
{
timestamp: "0:00 - 0:03",
visualDirection: Close-up dinâmico no ${name} sendo acionado em ação imediata.,
voiceover: Se você viu esse item viralizando na sua For You, hoje eu vou te mostrar a verdade.,
textOverlay: A VERDADE SOBRE ESSE PRODUTO! 🛑,
soundEffect: "Whoosh sonoro impactante"
},
{
timestamp: "0:03 - 0:12",
visualDirection: Demonstração passo a passo do funcionamento com iluminação clara e câmera estável.,
voiceover: Ele foi feito para resolver exatamente a dor de ${niche}. Olha como é simples de usar e o resultado é imediato.,
textOverlay: FÁCIL, RÁPIDO E PRÁTICO ⚡,
soundEffect: "Pop de satisfação"
},
{
timestamp: "0:12 - 0:22",
visualDirection: Exibição dos detalhes de construção, acessórios e durabilidade do produto.,
voiceover: O acabamento é resistente, dura muito tempo e substitui soluções que custam 3 vezes mais caro.,
textOverlay: QUALIDADE PREMIUM + DURABILIDADE 💎,
soundEffect: "Chime suave"
},
{
timestamp: "0:22 - 0:32",
visualDirection: Apontar o dedo firmemente para a parte inferior esquerda onde fica o botão da sacolinha amarela.,
voiceover: Tá com preço promocional e cupom de frete grátis ativo aqui no botão amarelo do TikTok Shop. Corre antes que acabe o estoque!,
textOverlay: 👇 CLIQUE NA SACOLINHA AMARELA COM FRETE GRÁTIS!,
soundEffect: "Cash register pop"
}
],
callToAction: Clique no botão amarelo do TikTok Shop no canto da tela e garanta o seu com desconto exclusivo e frete grátis!
}
],
creatorAffiliateEngine: {
idealCreatorProfile: Criadores nativos de ${category}, unboxing de achadinhos, rotina e reviews com entre 5k e 80k seguidores e alto engajamento em comentários.,
commissionStrategy: Oferecer 16% a 20% de comissão por venda + bônus de R$ 300 a R$ 500 para os criadores cujos vídeos gerarem mais de 50 pedidos.,
outreachDMScript: Oi [Nome]! Adorei a energia e a qualidade dos seus vídeos de dicas ✨ Estamos selecionando criadores de destaque para testar o nosso ${name} que está em alta no TikTok Shop. Queremos te enviar uma amostra gratuita completa + comissão de 18% em todas as vendas pelo seu link da sacolinha. Posso te enviar o pacote essa semana? Qual o seu melhor endereço?,
briefingGuidelines: [
"Mostrar o produto em pleno funcionamento nos primeiros 2 segundos (sem enrolação)",
"Gravar com áudio limpo e boa iluminação natural",
"Destacar o melhor custo-benefício e facilidade de uso",
"Encerrar com chamada clara para o botão amarelo da sacolinha"
]
},
pricingAndOfferArchitecture: {
anchorPrice: parseFloat(anchorPrice) || 129.90,
tiktokSpecialPrice: parseFloat(tiktokPrice) || 79.90,
bundleOffers: [
{
name: Kit Duplo Econômico (Leve 2 Unidades),
price: R$ ${(price * 1.7).toFixed(2)},
savings: Economia de 30% na 2ª unidade + Frete Grátis,
description: Excelente para quem quer presentear ou manter uma unidade reserva.
},
{
name: Combo Premium com Acessórios / Brinde Exclusivo,
price: R$ ${(price * 2.1).toFixed(2)},
savings: Brinde Especial,
description: Aumenta o ticket médio (AOV) com alta margem de contribuição.
}
],
urgencyTriggers: [
"Cupom de primeira compra no TikTok Shop",
"Selo de Frete Grátis ativado para todo o Brasil",
"Aviso de lote promocional por tempo limitado"
]
},
paidTrafficAndSparkAds: {
recommendedBudget: R$ 50/dia para teste inicial de 3 a 5 vídeos UGC -> Escalar para R$ 200 a R$ 500/dia nos criativos vencedores.,
campaignObjective: Conversão Direta via TikTok Shop (Product Sales / Spark Ads),
targetingClusters: [
Interesses: ${category}, Compras Online, Ofertas e Achadinhos,
Comportamento: Compradores frequentes e ativos no TikTok Shop,
Lookalike: Públicos semelhantes aos compradores da sacolinha
],
scaleStrategy: Filtrar os vídeos de criadores ou da conta oficial com maior tempo médio de retenção e impulsionar via Spark Ads para maximizar o ROAS.
},
tiktokSeoAndHashtags: {
highIntentKeywords: [
${name.toLowerCase().slice(0, 30)},
achadinhos tiktok shop ${category.toLowerCase()},
melhor ${niche.toLowerCase()} custo beneficio,
como usar ${name.toLowerCase().slice(0, 20)},
comprinhas do tiktok que valem a pena,
produtos virais tiktok shop brasil
],
broadHashtags: ["#TikTokShop", "#Achadinhos", "#Viral"],
nicheHashtags: [#${category.replace(/[^a-zA-Z0-9]/g, "")}, #${niche.replace(/[^a-zA-Z0-9]/g, "")}, "#DicasPraticas", "#Review"],
buyerHashtags: ["#TikTokMadeMeBuyIt", "#ComprinhasDoTikTok", "#AchadosDaInternet"]
},
sevenDayLaunchPlan: [
{
day: "Dia 1: Cadastro & Configuração de Listagem",
tasks: [
"Cadastrar o produto com título rico em palavras-chave no TikTok Shop Seller Center",
"Subir fotos nítidas em fundo branco e vídeo de capa demonstrativo",
"Configurar comissão aberta para afiliados em 18%"
]
},
{
day: "Dia 2: Disparo de Amostras para Criadores",
tasks: [
"Enviar mensagem de abordagem para 20 a 30 micro-criadores do nicho",
"Despachar amostras com rastreamento prioritário"
]
},
{
day: "Dia 3: Produção dos Primeiros Vídeos Internos",
tasks: [
"Gravar 4 variações de ganchos (Curiosidade, Antes/Depois, Teste Extremo, Problema/Solução)",
"Editar com legendas coloridas e cortes rápidos"
]
},
{
day: "Dia 4: Publicação & Resposta Rápida",
tasks: [
"Publicar os vídeos nos horários de maior engajamento",
"Responder todos os comentários rapidamente para ativar o algoritmo"
]
},
{
day: "Dia 5: Avaliação dos Primeiros Criativos",
tasks: [
"Monitorar taxa de cliques (CTR) e conversão na sacolinha",
"Coletar os códigos de autorização para Spark Ads dos melhores vídeos"
]
},
{
day: "Dia 6: Ativação de Spark Ads",
tasks: [
"Ligar campanha de tráfego pago nos criativos mais engajados",
"Otimizar orçamento com foco em CPA abaixo da meta"
]
},
{
day: "Dia 7: Escala & Otimização de Margem",
tasks: [
"Ativar promoções de kit duplo para elevar o ticket médio",
"Aumentar verba nos anúncios com melhor retorno (ROAS)"
]
}
]
};
}
The following action was requested:
Edit file /server.tsThe action produced the following result:
The following changes were made by an unspecified tool call (nil ToolCall) to: /server.ts.
[diff_block_start]
@@ -23,6 +23,43 @@
});
}
+// Helper to call Gemini models with resilient model fallbacks and retry on 503/429
+async function generateContentWithFallback(
ai: GoogleGenAI,
primaryModel: string,
modelsToTry: string[],
options: {
contents: string;
config?: any;
}
+): Promise<{ response: any; modelUsed: string }> {
const allModels = [primaryModel, ...modelsToTry.filter((m) => m !== primaryModel)];
let lastError: any = null;
for (const model of allModels) {
for (let attempt = 1; attempt <= 2; attempt++) {
code
Code
try {
code
Code
const response = await ai.models.generateContent({
code
Code
model,
code
Code
contents: options.contents,
code
Code
config: options.config,
code
Code
});
code
Code
return { response, modelUsed: model };
code
Code
} catch (err: any) {
code
Code
lastError = err;
code
Code
console.warn(`[Gemini API] Error calling model '${model}' (attempt ${attempt}):`, err?.message || err);
code
Code
// If it's a 503 (high demand) or 429 (rate limit), wait a bit and try next or retry
code
Code
if (attempt === 1) {
code
Code
await new Promise((res) => setTimeout(res, 800));
code
Code
}
code
Code
}
}
}
// If all models and retries failed, throw lastError
throw lastError || new Error("All Gemini model attempts failed.");
+}
// Endpoint: Live TikTok Trends Search via Google Search Grounding & Gemini 3.7 Flash
app.post("/api/tiktok/live-trends", async (req, res) => {
try {
@@ -63,14 +100,16 @@
]
}`;
const response = await ai.models.generateContent({
code
Code
model: "gemini-3.7-flash",
const { response, modelUsed } = await generateContentWithFallback(
code
Code
ai,
code
Code
"gemini-2.5-flash",
code
Code
["gemini-3.7-flash", "gemini-2.5-pro"],
code
Code
{
 contents: prompt,
 config: {
   responseMimeType: "application/json",
code
Code
tools: [{ googleSearch: {} }],
   systemInstruction: "Você é um analista sênior de inteligência de mercado para TikTok Shop e e-commerce de resposta direta. Sempre retorne dados práticos, realistas e orientados a alto retorno sobre investimento em JSON válido.",
code
Code
},
code
Code
}
});
const responseText = response.text || "{}";
@@ -95,6 +134,7 @@
success: true,
data: parsedData,
sources: webSources,
code
Code
modelUsed,
});
} catch (error: any) {
console.error("Error in /api/tiktok/live-trends:", error);
@@ -165,14 +205,16 @@
Responda ESTRITAMENTE em formato JSON compatível.`;
const response = await ai.models.generateContent({
code
Code
model: "gemini-3.7-flash",
const { response, modelUsed } = await generateContentWithFallback(
code
Code
ai,
code
Code
"gemini-2.5-flash",
code
Code
["gemini-3.7-flash", "gemini-2.5-pro"],
code
Code
{
 contents: prompt,
 config: {
   responseMimeType: "application/json",
   systemInstruction: "Você é um estrategista em crescimento e tráfego direto para TikTok Shop. Gere respostas ricas, detalhadas, práticas e sem enrolação, prontas para gerar vendas em formato JSON válido.",
code
Code
},
});
code
Code
}
});
const responseText = response.text || "{}";
let parsedStrategy;
@@ -186,6 +228,7 @@
res.json({
success: true,
data: parsedStrategy,
code
Code
modelUsed,
});
} catch (error: any) {
console.error("Error in /api/tiktok/generate-strategy:", error);
[diff_block_end]
Please note that the above snippet only shows the MODIFIED lines from the last change. It shows up to 3 lines of unchanged lines before and after the modified lines. The actual file contents may have many more lines not shown.The following action was requested:
View contents of file /src/App.tsx from lines 30 to 120The action produced the following result:
File Path: /src/App.tsx
Total Lines: 270
Total Bytes: 10190
Showing lines 30 to 120
The following code has been modified to include a line number before every line, in the format: <line_number>: <original_line>. Please note that any changes targeting the original code should remove the line number, colon, and leading space.
30:
The above content does NOT show the entire file contents. If you need to view any lines of the file which were not shown to complete your task, call this tool again to view those lines.The following action was requested:
View contents of file /src/App.tsx from lines 115 to 200The action produced the following result:
File Path: /src/App.tsx
Total Lines: 270
Total Bytes: 10190
Showing lines 115 to 200
The following code has been modified to include a line number before every line, in the format: <line_number>: <original_line>. Please note that any changes targeting the original code should remove the line number, colon, and leading space.
115:
The above content does NOT show the entire file contents. If you need to view any lines of the file which were not shown to complete your task, call this tool again to view those lines.The following action was requested:
Edit file /src/App.tsxThe action produced the following result:
The following changes were made by an unspecified tool call (nil ToolCall) to: /src/App.tsx.
[diff_block_start]
@@ -6,6 +6,7 @@
import { CustomProductAnalyzer } from "./components/CustomProductAnalyzer";
import { CURATED_TRENDING_PRODUCTS, PRESET_STRATEGIES } from "./data/curatedTrends";
import { TrendingProduct, ProductStrategy, ActiveTab } from "./types";
+import { generateDynamicFallbackStrategy } from "./utils/fallbackGenerator";
import confetti from "canvas-confetti";
export default function App() {
@@ -58,21 +59,20 @@
spread: 70,
origin: { y: 0.7 },
});
code
Code
} else {
code
Code
console.error("Strategy generation failed:", data.error);
code
Code
if (PRESET_STRATEGIES["trend-alecrim-serum"]) {
code
Code
setCurrentStrategy(PRESET_STRATEGIES["trend-alecrim-serum"]);
code
Code
}
code
Code
return;
 }
} catch (err) {
code
Code
console.error("Network error generating strategy:", err);
code
Code
if (PRESET_STRATEGIES["trend-alecrim-serum"]) {
code
Code
setCurrentStrategy(PRESET_STRATEGIES["trend-alecrim-serum"]);
code
Code
}
} finally {
code
Code
setIsLoadingStrategy(false);
}
};
code
Code
console.warn("Backend strategy call failed, applying dynamic high-quality fallback:", err);
}
// Graceful Fallback
const fallback =
code
Code
PRESET_STRATEGIES[product.id] ||
code
Code
PRESET_STRATEGIES["trend-furadeira-impacto"] ||
code
Code
generateDynamicFallbackStrategy(product);
setCurrentStrategy(fallback);
setIsLoadingStrategy(false);
}
// Handle Live Trends Scan
const handleRefreshLiveTrends = async (cat?: string, query?: string) => {
@@ -155,10 +155,14 @@
spread: 80,
origin: { y: 0.7 },
});
code
Code
return;
 }
} catch (err) {
code
Code
console.error("Error analyzing custom product:", err);
code
Code
console.warn("Error calling custom product strategy, generating dynamic fallback:", err);
} finally {
code
Code
// Generate dynamic custom strategy if backend experienced temporary demand spike
code
Code
const fallback = generateDynamicFallbackStrategy(customProductData, customPrompt);
code
Code
setCurrentStrategy(fallback);
 setIsLoadingStrategy(false);
}
};
@@ -183,10 +187,14 @@
spread: 70,
origin: { y: 0.7 },
});
code
Code
return;
 }
} catch (err) {
code
Code
console.error("Error regenerating strategy:", err);
code
Code
} finally {
code
Code
// Generate refined dynamic strategy
code
Code
const fallback = generateDynamicFallbackStrategy(selectedProduct, feedbackPrompt);
code
Code
setCurrentStrategy(fallback);
 setIsLoadingStrategy(false);
}
};
[diff_block_end]
Please note that the above snippet only shows the MODIFIED lines from the last change. It shows up to 3 lines of unchanged lines before and after the modified lines. The actual file contents may have many more lines not shown.The following action was requested:
Restarting dev server...The action produced the following result:
Dev server restarted successfullyThe following action was requested:
Running linter...The action produced the following result:
Linting completed successfully
Output:
react-example@0.0.0 lint
tsc --noEmit
The following action was requested:
Building applet...The action produced the following result:
Build succeeded - the applet is compiled
lightbulb_tips
  

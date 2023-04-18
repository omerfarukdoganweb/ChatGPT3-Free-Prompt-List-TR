# ChatGPT3 Prompt Engineering
Guide and framework for creating ChatGPT3 Prompts

![GitHub Repo stars](https://img.shields.io/github/stars/mattnigh/ChatGPT3-Prompt-Engineering?style=social) - **Our GitHub Stars!**

[![Deploy Jekyll site to Pages](https://github.com/mattnigh/ChatGPT3-Prompt-Engineering/actions/workflows/jekyll.yml/badge.svg)](https://github.com/mattnigh/ChatGPT3-Prompt-Engineering/actions/workflows/jekyll.yml)
 ![GitHub last commit](https://img.shields.io/github/last-commit/mattnigh/ChatGPT3-Prompt-Engineering?style=plastic)

This repo was developed by [@mattnigh](https://github.com/mattnigh). 
Follow or connect with me on [my LinkedIn](https://www.linkedin.com/in/mattnigh/). 

### Prompt Mühendisliği Nedir?

Prompt mühendisliği, ChatGPT gibi bir dil modeline yanıt üretmek için verilen ilk metin veya giriş (prompt) tasarlamak ve geliştirmek için yapılan bir süreçtir. Bu süreç, modelin belirli bir ton, tarz veya içerik türü üretmesine yol gösteren ipuçları tasarlamayı içerir.

## Prompt Mühendisliği: Temel İlkeler

- Somut ve açık bir dil kullanın.
- Modelin konunun uzmanıymış gibi davranmasını isteyin.
- Modelin belirli bir kişi veya kişilerin bir kombinasyonu gibi davranmasını isteyin.
- Orta düzeyden karmaşık görevlere özellikle 'adım adım' düşünmesini isteyin.
- Çıktılarla deney yapın, Bana 10 farklı örnek verin.
- Sonuçları geliştirin, Bu daha çekici olacak şekilde yeniden yazın, daha açık bir dil kullanın ve daha okunaklı hale getirmek için madde işaretleri kullanın.

## Prompt Mühendisliği veya ChatGPT Kullanmamanız Gereken Durumlar

- %100 güvenilirliğe ihtiyaç duyduğunuz zamanlar
- Modelin çıktısının doğruluğunu değerlendirmenin bir yolunun olmadığı zamanlar
- Modelin eğitim verilerinde olmayan içerikler oluşturmanız gerektiği zamanlar

----

# ChatGPT Promptları Oluşturma: Çatı

ChatGPT için prompt oluştururken bir prompt çerçevesi kullanmak faydalı olabilir. Çerçeveler, prompt oluşturma sürecine yapısal bir çerçeve ve netlik sağlar. Prompt oluşturma sürecini net ve belirgin adımlara ayırır. ChatGPT ile kendi kullanımım ve denemelerim için aşağıdaki çerçeveyi (CRISPE) oluşturdum.

### CRISPE Prompt Framework:

- **Kapasite ve Rol:** ChatGPT hangi rol(ler) üstlenecek?  
- **Kavrayış:** Talebinizin arkasındaki iç görü, arka plan ve bağlamı sağlar.
- **Açıklama:** ChatGPT'den ne istediğinizi ifade eder.
- **Kişilik:** ChatGPT'nin nasıl cevap vereceğiyle ilgili stil, kişilik veya tarz.
- **Deney:** ChatGPT'den size birden fazla örnek sunmasını isteme.

## Promptlar Nasıl Oluşturulur -> CRISPE Örneği

<table>
  <tr>
   <td>Adım
   </td>
   <td>Örnek Prompt
   </td>
  </tr>
  <tr>
   <td>Kapasite ve Rol
   </td>
   <td>`Makine öğrenimi çerçeveleri konusunda yazı yazmak ve konuda uzman olarak hareket etmek, aynı zamanda bir uzman blog yazarı olarak hareket etmek.`
   </td>
  </tr>
  <tr>
   <td>Kavrayış
   </td>
   <td>`Bu blogun hedef kitlesi, makine öğrenimi alanındaki en son gelişmeleri öğrenmek isteyen teknik profesyonellerdir.`
   </td>
  </tr>
  <tr>
   <td>Açıklama
   </td>
   <td>`En popüler makine öğrenimi çerçevelerinin kapsamlı bir genel bakışını sağlayın ve bunların güçlü ve zayıf yönlerini dahil edin. Bu çerçevelerin farklı endüstrilerde nasıl başarılı bir şekilde kullanıldığını göstermek için gerçek hayat örnekleri ve vaka çalışmaları da dahil edin.`
   </td>
  </tr>
  <tr>
   <td>Kişilik
   </td>
   <td>`Cevap verirken, Andrej Karpathy, Francois Chollet, Jeremy Howard ve Yann LeCun'un yazı stillerinin bir karışımını kullanın.`
   </td>
  </tr>
  <tr>
   <td>Deney
   </td>
   <td>`Bana birden fazla farklı örnek verin.`
   </td>
  </tr>
</table>


Bir makine öğrenimi frameworkleri konusunda yazı yazan bir uzman olarak hareket et. Bu blogun hedef kitlesi, makine öğrenimindeki en son gelişmeleri öğrenmek isteyen teknik profesyonellerdir. En popüler makine öğrenimi frameworklerinin kapsamlı bir genel bakışını sağla. Bu frameworklerin güçlü ve zayıf yönlerini belirt. Bu frameworklerin farklı endüstrilerde başarılı bir şekilde kullanıldığını göstermek için gerçek yaşam örnekleri ve vaka çalışmaları ekle. Cevap verirken, Andrej Karpathy, Francois Chollet, Jeremy Howard ve Yann LeCun'un yazı stillerinin bir karışımını kullan. "Başka bir örnek ver" veya "Birden fazla örnek ver" diyerek cevabını çeşitlendirmeni isteyebilirim.


## Promptu İyileştirme: "Ruhsuz Yazmayı" Düzeltme

- **Yaratıcılığı teşvik edin:** "Var olan belgeyi daha yaratıcı, çekici ve benzersiz hale getirmek için yeniden yazın."`
- **Hikayeye odaklanın:** `"Var olan belgeyi, karşılaşılan zorlukları ve sunulan çözümleri vurgulayan etkileyici bir hikayeye dönüştürün."
- **İkna edici dil kullanın:** `"Var olan belgeyi, ikna edici dil ve teknikler kullanarak daha ikna edici ve etkileyici hale getirin."
- **Duyguyu vurgulayın:** `"Var olan belgeye duygusal dil ve duyusal detaylar ekleyerek daha alakalı ve etkileyici hale getirin."
- **Duyusal detayları kullanın:** `"Var olan belgeyi canlandırmak ve okuyucuyu daha fazla etkilemek için duyusal detaylar ve betimleyici dil ekleyin."
- **İçeriği özlü hale getirin:** `"Var olan belgeyi gereksiz bilgileri çıkararak daha özlü ve net hale getirin."
- **Ana noktaları vurgulayın:** `"Var olan belgeyi yeniden yazarak ana noktaları vurgulayın ve daha etkili hale getirin."
- **Canlı dil kullanın:** `"Var olan belgeyi daha etkileyici hale getirmek için canlı dil ve betimleyici sıfatlar kullanın."
- **Aciliyet duygusu yaratın:** "ar olan belgeyi, aciliyet duygusu ekleyerek ve hemen harekete geçme ihtiyacını vurgulayarak daha etkili hale getirin."
- **Objectionları ele alın:** "Var olan belgeyi yeniden düzenleyerek, içeriğe olası itirazları öngörerek ve ele alarak daha etkili hale getirin."
- **İçeriği kişiselleştirin:** "Var olan belgeyi kişiselleştirerek ve okuyucuyla daha ilişkisel hale getirerek daha etkileyici hale getirin."

## Prompt İyileştirme: Okunabilirliği Artırın

- **Açık ve özlü bir dil kullanın:** "Teknik kavramları basit terimlerle açıklayın."
- **Görsel yardımcılar ekleyin:** "Karmaşık kavramları açıklamak için mermaid.js kullanarak diyagramlar ekleyebilirsiniz (düşük güvenilirlik)."
- **Başlıklar ve alt başlıklar kullanın:** "Belgeyi açık başlıklar ve alt başlıklarla bölün."
- **Anahtar noktaları vurgulayın:** "Önemli bilgileri kalın veya eğik yazı kullanarak vurgulayın."
- **Gerçek hayat örnekleri ekleyin:** "Kavramları daha anlaşılır hale getirmek için vaka çalışmaları veya gerçek dünya örnekleri ekleyin."
- **Net ve tutarlı biçimlendirme kullanın:** "Belge boyunca tutarlı bir yazı tipi, yazı tipi boyutu ve düzen kullanın."
- **Analogi ve karşılaştırmaları kullanın:** "Karmaşık fikirleri analogi veya karşılaştırmalar kullanarak açıklayın."
- **Eylemli dil kullanın:** "Cümleleri daha etkileyici ve takip etmesi daha kolay hale getirmek için eylemli dil kullanın."

## Prompts for Web Developers

- "What is the difference between HTML, CSS, and JavaScript?"
- "What is AJAX and how is it used in web development?"
- "Can you help me review this HTML code for best practices?"
- "What are some common JavaScript debugging techniques?"
- "What is the syntax for using media queries in CSS?"
- "How can I make sure my code is accessible to users with disabilities?"
- "How do I structure and organize my CSS to make it scalable?"
- "What are some good resources to learn JavaScript design patterns?"
- "Can you help me optimize this code for performance?"
- "What are some common cross-browser compatibility issues and how to resolve them?"
- "How can I implement error handling in my JavaScript code?"
- "What are some principles to keep in mind when writing maintainable and scalable code?"
- "Can you review this code and suggest any improvements for maintainability?"
- "Can you review this code and suggest improvements for performance?"
- "What are the best practices for structuring HTML, CSS, and JavaScript code?"
- "What is the best way to optimize this code for search engines?"

## ChatGPT3 can also Pair Program

Ask the model to act as a...

- **Technical advisor:** "Act as a Technical advisor and provide technical insight on the implementation of this code."
- **Mentor:** "Act as a Mentor and review this code, providing feedback on areas for improvement."
- **Quality assurance:** "Act as a Quality assurance and review this code to ensure it meets best practices, standards, and - requirements."
- **Code reviewer:** "Act as a Code reviewer and provide feedback on the readability, efficiency, and performance of this code."
- **Debugging assistant:** "Act as a Debugging assistant and suggest solutions to the technical issues found in the code."
- **Compliance checker:** "Act as a Compliance checker and verify if this code is compliant with industry regulations and standards."
- **Code optimization specialist:** "Act as a Code optimization specialist and suggest improvements to optimize the code's performance."
- **Accessibility Expert:** "Act as an Accessibility Expert and review this code, suggesting modifications to improve accessibility."
- **Search engine optimization specialist:** "Act as a Search engine optimization specialist and review this code, suggesting improvements for better search engine optimization."
- **Performance analyst:** "Act as a Performance analyst and evaluate the performance of this code, suggesting improvements."

---

## Recommended Resources

- [OpenAI CookBook](https://github.com/openai/openai-cookbook/): Shares example code for common tasks with the OpenAI API
- [OpenAI API](https://beta.openai.com/docs/api-reference/introduction): The OpenAI API is a RESTful API that allows you to interact with the OpenAI API using any programming language.

---

*Want to know how this was made?*  It is a passion project using ChatGPT and the below resources:

- [Just the Docs](https://just-the-docs.github.io/just-the-docs/)
- [GitHub Pages](https://docs.github.com/en/pages)
- [Jekyll](https://jekyllrb.com)
- [GitHub Pages / Actions workflow](https://github.blog/changelog/2022-07-27-github-pages-custom-github-actions-workflows-beta/)

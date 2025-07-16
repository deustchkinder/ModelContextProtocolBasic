# ModelContextProtocolBasic
>>dotnet add package Microsoft.Extensions.Hosting
>>dotnet add package ModelContextProtocol --prerelease
>>dotnet build
>>npx @modelcontextprotocol/inspector dotnet run
>>

Bağlam(Context), modelimizin karar vermesine yardımcı olan tüm geçici bilgileri ifade etmektedir. Mesela, sohbet geçmişi, kullanıcı tercihleri, işlem durumları ve bunlar gibi ekstradan harici veriler o anki yapay zekayla olan iletişimin verisel havuzunu yani bir başka deyişle bağlamını oluşturmaktadır. Yapay Zeka Modellerinde kullanıcı etkileşimi sırasında kredi kartı numarası, şifre vesaire gibi gereksiz ya da hasssas bilgilerin cereyan etmesi yani açığa çıkması söz konusu olabilir. İşte böyle bir duruma bağlama eklenilerek istenilmeyen durumları filtreleyebiliriz. Uzun bağlamları sıkıştırarak modelin işlem sınırlarını aşmasını engelleyerek **token_limits** optimize edilebilir ve işlenen bir bağlamı farklı modeller veya sistemler arasında taşınabilir bir hale getirebiliriz.

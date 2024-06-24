# Blog post http://marylia.dev/?postID=L-otel-sdk-api


🇧🇷 
Neste repositório você irá encontrar 3 pastas, uma para cada tipo de instrumentação detalhada em http://marylia.dev/?postID=L-otel-sdk-api

Para rodar cada uma delas individualmente:
1. No seu terminal, navegue até a pasta que deseja testar (auto-instrumentation, sdk, manual)
2. Atualize os valores do arquivo `env_variables.md`, copie e cole o conteúdo desse arquivo no seu terminal
3. Rode `npm install`
4. Rode sua aplicação:
    - Auto-instrumentation: `npx ts-node app.ts`
    - SDK: `npx ts-node --require ./instrumentation.ts app.ts`
    - Manual: `npx ts-node --require ./instrumentation.ts app.ts`


🇨🇦
In this repo, you will find 3 folders, one for each instrumentation mode detailed on http://marylia.dev/?postID=L-otel-sdk-api

To run each one individually:
1. In your terminal, open the folder you want to test (auto-instrumentation, sdk, manual)
2. Update the values from the file `env_variables.md`, copy and paste its content in your terminal
3. Run `npm install`
4. Run your application:
    - Auto-instrumentation: `npx ts-node app.ts`
    - SDK: `npx ts-node --require ./instrumentation.ts app.ts`
    - Manual: `npx ts-node --require ./instrumentation.ts app.ts`

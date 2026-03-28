# Copilist
A BYOK list fot GitHub Copilot for VS Code.

Click provider names to redirect to providers' API Key management page.

## [Xiaomi MiMo](https://platform.xiaomimimo.com/#/console/api-keys)
```json
{
    "name": "Xiaomi",
    "vendor": "customoai",
    "models": [
        {
            "name": "MiMo V2 Flash",
            "url": "https://api.xiaomimimo.com/v1",
            "toolCalling": true,
            "vision": false,
            "thinking": true,
            "maxInputTokens": 262144
            "id": "mimo-v2-flash"
        }
    ],
    "apiKey": "YOUR_API_KEY"
}
```

## [OpenCode Zen](https://opencode.ai/zen) (WIP)
```json
{
    "name": "OpenCode Zen",
    "vendor": "customoai",
    "apiKey": "YOUR_API_KEY",
    "models": [
        {
            "id": "big-pickle",
            "name": "Big Pickle",
            "url": "https://opencode.ai/zen/v1",
            "toolCalling": true,
            "vision": false,
            "thinking": true,
            "maxInputTokens": 128000,
            "maxOutputTokens": 16000
        },
        {
            "id": "minimax-m2.5-free",
            "name": "MiniMax M2.5 Free",
            "url": "https://opencode.ai/zen/v1",
            "toolCalling": true,
            "vision": false,
            "thinking": false,
            "maxInputTokens": 128000,
            "maxOutputTokens": 16000
        },
        {
            "id": "trinity-large-preview-free",
            "name": "Trinity Large Preview",
            "url": "https://opencode.ai/zen/v1",
            "toolCalling": true,
            "vision": false,
            "thinking": false,
            "maxInputTokens": 128000,
            "maxOutputTokens": 16000
        },
        {
            "id": "trinity-large-preview-free",
            "name": "Trinity Large Preview",
            "url": "https://opencode.ai/zen/v1",
            "toolCalling": true,
            "vision": false,
            "thinking": false,
            "maxInputTokens": 128000,
            "maxOutputTokens": 16000
        }
    ]
}
```

## [Mistral](https://console.mistral.ai/home?profile_dialog=api-keys) (WIP)
```json
{
    "name": "Mistral",
    "vendor": "customoai",
    "apiKey": "YOUR_API_KEY",
    "models": [
        {
            "id": "mistral-vibe-cli-latest",
            "name": "Mistral Vibe CLI",
            "url": "https://api.mistral.ai/v1",
            "toolCalling": true,
            "vision": false,
            "maxInputTokens": 256000
        }
    ]
}
```

## [Mistral (Codestral)](https://console.mistral.ai/codestral)
```json
{
    "name": "Codestral",
    "vendor": "customoai",
    "apiKey": "YOUR_API_KEY",
    "models": [
        {
            "id": "codestral-latest",
            "name": "Codestral",
            "url": "https://codestral.mistral.ai/v1",
            "toolCalling": true,
            "vision": false,
            "maxInputTokens": 128000
        }
    ]
}
```

# "Not recommended" providers

## ~~Qwen Code~~
> [!CAUTION]
> **It may violate [Qwen Terms of Service](https://qwen.ai/termsservice).**
>
> **NOT RECOMMENDED ANYMORE.**

~~Go to [qwen-code-oai-proxy](https://github.com/aptdnfapt/qwen-code-oai-proxy) for more information about the local proxy.~~
```json
{
    "name": "Qwen Code (Local Proxy)",
    "vendor": "customoai",
    "models": [
        {
            "id": "coder-model",
            "name": "Coder Model",
            "url": "http://localhost:8080/v1",
            "toolCalling": true,
            "vision": true,
            "thinking": true,
            "maxInputTokens": 65536
        }
    ]
}
```

## ChatAnywhere (WIP)
> [!NOTE]
> This provider's free API key may not compatible with Copilot.

```json
{
    "name": "ChatAnywhere",
    "vendor": "customoai",
    "models": [
        {
            "name": "GPT-5 mini",
            "url": "https://api.chatanywhere.tech",
            "toolCalling": true,
            "vision": true,
            "thinking": true,
            "maxInputTokens": 4096,
            "maxOutputTokens": 4096,
            "id": "gpt-5-mini"
        }
    ],
    "apiKey": "YOUR_API_KEY"
}
```
## ~~iFlow~~

> [!IMPORTANT]
> iFlow CLI will officially shut down on April 17, 2026 (Beijing Time). Please [migrate to Qoder](https://platform.iflow.cn/email-collect).

<details>

<summary>Still want to use? </summary>

```json
{
    "name": "iFlow",
    "vendor": "customoai",
    "models": [
        {
            "name": "iFlow-ROME",
            "url": "https://apis.iflow.cn/v1",
            "toolCalling": true,
            "vision": false,
            "thinking": false,
            "maxInputTokens": 192000,
            "maxOutputTokens": 64000,
            "id": "iflow-rome-30ba3b"
        },
        {
            "name": "Qwen3-Coder-Plus",
            "url": "https://apis.iflow.cn/v1",
            "toolCalling": true,
            "vision": false,
            "thinking": false,
            "maxInputTokens": 960000,
            "maxOutputTokens": 64000,
            "id": "qwen3-coder-plus"
        },
        {
            "name": "Qwen3-Max",
            "url": "https://apis.iflow.cn/v1",
            "toolCalling": true,
            "vision": false,
            "thinking": false,
            "maxInputTokens": 224000,
            "maxOutputTokens": 32000,
            "id": "qwen3-max"
        },
        {
            "name": "Qwen3-VL-Plus",
            "url": "https://apis.iflow.cn/v1",
            "toolCalling": true,
            "vision": true,
            "thinking": false,
            "maxInputTokens": 224000,
            "maxOutputTokens": 32000,
            "id": "qwen3-vl-plus"
        },
        {
            "name": "Kimi-K2-Instruct-0905",
            "url": "https://apis.iflow.cn/v1",
            "toolCalling": true,
            "vision": false,
            "thinking": false,
            "maxInputTokens": 192000,
            "maxOutputTokens": 64000,
            "id": "kimi-k2-0905"
        },
        {
            "name": "Qwen3-Max-Preview",
            "url": "https://apis.iflow.cn/v1",
            "toolCalling": true,
            "vision": false,
            "thinking": false,
            "maxInputTokens": 224000,
            "maxOutputTokens": 32000,
            "id": "qwen3-max-preview"
        },
        {
            "name": "GLM-4.6",
            "url": "https://apis.iflow.cn/v1",
            "toolCalling": true,
            "vision": false,
            "thinking": false,
            "maxInputTokens": 72000,
            "maxOutputTokens": 128000,
            "id": "glm-4.6"
        },
        {
            "name": "Kimi-K2",
            "url": "https://apis.iflow.cn/v1",
            "toolCalling": true,
            "vision": false,
            "thinking": false,
            "maxInputTokens": 64000,
            "maxOutputTokens": 64000,
            "id": "kimi-k2"
        },
        {
            "name": "DeepSeek-V3.2-Exp",
            "url": "https://apis.iflow.cn/v1",
            "toolCalling": true,
            "vision": false,
            "thinking": true,
            "maxInputTokens": 64000,
            "maxOutputTokens": 64000,
            "id": "deepseek-v3.2"
        },
        {
            "name": "DeepSeek-R1",
            "url": "https://apis.iflow.cn/v1",
            "toolCalling": true,
            "vision": false,
            "thinking": true,
            "maxInputTokens": 96000,
            "maxOutputTokens": 32000,
            "id": "deepseek-r1"
        },
        {
            "name": "DeepSeek-V3-671B",
            "url": "https://apis.iflow.cn/v1",
            "toolCalling": true,
            "vision": false,
            "thinking": false,
            "maxInputTokens": 96000,
            "maxOutputTokens": 32000,
            "id": "deepseek-v3"
        },
        {
            "name": "Qwen3-32B",
            "url": "https://apis.iflow.cn/v1",
            "toolCalling": true,
            "vision": false,
            "thinking": false,
            "maxInputTokens": 96000,
            "maxOutputTokens": 32000,
            "id": "qwen3-32b"
        },
        {
            "name": "Qwen3-235B-A22B-Instruct",
            "url": "https://apis.iflow.cn/v1",
            "toolCalling": true,
            "vision": false,
            "thinking": false,
            "maxInputTokens": 192000,
            "maxOutputTokens": 64000,
            "id": "qwen3-235b-a22b-instruct"
        },
        {
            "name": "Qwen3-235B-A22B-Thinking",
            "url": "https://apis.iflow.cn/v1",
            "toolCalling": true,
            "vision": false,
            "thinking": true,
            "maxInputTokens": 192000,
            "maxOutputTokens": 64000,
            "id": "qwen3-235b-a22b-thinking-2507"
        },
        {
            "name": "Qwen3-235B-A22B",
            "url": "https://apis.iflow.cn/v1",
            "toolCalling": true,
            "vision": false,
            "thinking": false,
            "maxInputTokens": 96000,
            "maxOutputTokens": 32000,
            "id": "qwen3-235b"
        }
    ],
    "apiKey": "YOUR_API_KEY"
}
```

</details>

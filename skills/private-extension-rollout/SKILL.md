# private-extension-rollout

Use this skill when migrating a capability from open-source runtime into internal extension packages.

## Checklist

1. Keep open-source side as contract + disabled fallback.
2. Move implementation into private extension package.
3. Declare capability in extension manifest.
4. Ensure WS/tool_result schema remains stable.
5. Add audit and capability registry visibility checks.

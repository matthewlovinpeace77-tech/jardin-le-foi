NEXT_PUBLIC_SUPABASE_URL=https://qkpyeqinynmmzxpentif.supabase.co
NEXT_PUBLIC_SUPABASE_PUBLISHABLE_KEY=sb_publishable_qcvUNqFnKbajxfVnCFM16A_H9VJy27bpm install @supabase/supabase-js @supabase/ssrsb_secret_Z4emqaPir_WflbMGJtXf8w__1XPYptp
https://qkpyeqinynmmzxpentif.supabase.co/rest/v1/
1. Add MCP server
Add the MCP server to your project config using the command line.
Code:
File: Code
```
claude mcp add --scope project --transport http supabase "https://mcp.supabase.com/mcp?project_ref=qkpyeqinynmmzxpentif&features=docs%2Caccount%2Cdatabase%2Cdebugging%2Cdevelopment%2Cfunctions%2Cbranching"
```

2. Authenticate
After configuring the MCP server, you need to authenticate. Run this in a regular terminal, not an IDE extension.
Details:
Select the supabase server, then Authenticate to begin the flow.
Code:
File: Code
```
claude /mcp
```

3. Install Agent Skills (optional)
Agent Skills give AI coding tools ready-made instructions, scripts, and resources for working with Supabase more accurately and efficiently.
Code:
File: Code
```
npx skills add supabase/agent-skills
```

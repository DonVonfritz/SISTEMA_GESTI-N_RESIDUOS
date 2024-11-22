
[FASE4_GestiónResiduos_HTML_EF.txt](https://github.com/user-attachments/files/17877258/FASE4_GestionResiduos_HTML_EF.txt)
SISTEMA DE GESTIÓN RESIDUOS

CÓDIGO HTML  

[FASE4_GestiónResiduos_HTML_EF.txt](https://github.com/user-attachments/files/17877253/FASE4_GestionResiduos_HTML_EF.txt)

Universidad Nacional Abierta y a Distancia  UNAD

Vicerrectoría Académica y de Investigación

Curso: Proyecto de Grado Código: 202016907


Guía de actividades y rúbrica de evaluación – Fase 4
Desarrollo de la propuesta Ingenieril del proyecto

Omar Hernán Velandia Toca
Erick Andres Fajardo Bejarano
Diego Daniel Cruz Torres

202016907 - Proyecto de grado

Tutor.
Director: Ing. Daniel Andrés Guzmán Arévalo
Profesor. Ing. Cesar Alberto Galindo Daza

Universidad Nacional Abierta y a Distancia UNAD
Vicerrectoría Académica y de Investigación
Escuela de Ciencias Básicas, Tecnología e Ingeniería
Santafé de Bogotá D.C. – Noviembre 2024

[Uplo



---------------------------SISTEMA DE GESTIÓN DE RESIDUOS--------------

Código  HTML, CSS, JAVASCRIPT

-------------------------



    
<!DOCTYPE html>
<html lang="en">
  <head>

      <link rel="preload" href="&#47;api&#47;user&#47;state?team_id=1302143616126948636&amp;omit_core_data=1&amp;file_key=cmBOQvP4AafvYuiRX3fFtq&amp;fuid=1302143614040137592" as="fetch" crossorigin="anonymous"/>
      <link rel="preload" href="&#47;api&#47;session&#47;state?fuid=1302143614040137592" as="fetch" crossorigin="anonymous"/>

    <meta charset="utf-8">

    <meta name="bundle_flavor" content="[&quot;prototype_app&quot;, &quot;prototype_app&quot;]" />

    <meta name="is_preload_streaming" content="true" />

        <meta name="twitter:card" content="player">
    <meta name="twitter:site" content="@figma">
    <meta name="twitter:title" content="SISTEMA DE GESTIÓN DE RESIDUOS">
    <meta name="twitter:player" content="https://www.figma.com/embed?embed_host=twitter&url=https:&#47;&#47;www.figma.com&#47;proto&#47;cmBOQvP4AafvYuiRX3fFtq&#47;SISTEMA-DE-GESTI%25C3%2593N-DE-RESIDUOS?node-id=50-144&amp;node-type=canvas&amp;t=gmGycp28Bd6yGgYZ-0&amp;scaling=scale-down&amp;content-scaling=fixed&amp;page-id=0%3A1&amp;starting-point-node-id=17%3A11&amp;hide-ui=1">
    <meta name="twitter:player:width" content="800">
    <meta name="twitter:player:height" content="450">
    <meta name="twitter:image" content="https:&#47;&#47;www.figma.com&#47;file&#47;cmBOQvP4AafvYuiRX3fFtq&#47;thumbnail?ver=thumbnails%2F67e301c3-d56c-4fe2-b42d-aa0d53bcb662&amp;t=gmGycp28Bd6yGgYZ-0">

    <meta property="og:url" content="https:&#47;&#47;www.figma.com&#47;proto&#47;cmBOQvP4AafvYuiRX3fFtq&#47;SISTEMA-DE-GESTI%25C3%2593N-DE-RESIDUOS?node-id=50-144&amp;node-type=canvas&amp;t=gmGycp28Bd6yGgYZ-0&amp;scaling=scale-down&amp;content-scaling=fixed&amp;page-id=0%3A1&amp;starting-point-node-id=17%3A11&amp;hide-ui=1" />
    <meta property="og:description" content="Created with Figma" />
    <meta property="og:image" content="https:&#47;&#47;www.figma.com&#47;file&#47;cmBOQvP4AafvYuiRX3fFtq&#47;thumbnail?ver=thumbnails%2F67e301c3-d56c-4fe2-b42d-aa0d53bcb662&amp;t=gmGycp28Bd6yGgYZ-0">
    <meta property="og:image:width" content="798" />
    <meta property="og:image:height" content="159" />
    <meta property="og:image:user_generated" content="true" />
    <meta property="og:type" content="article" />
    <meta property="og:article:published_time" content="2024-11-18 18:47:39 UTC" />
    <meta property="og:article:modified_time" content="2024-11-22 15:43:44 UTC" />
    <meta property="og:article:section" content="Design" />

    <meta name="description" content="Created with Figma" >

    <link rel="alternate" type="application/json+oembed" href="https:&#47;&#47;www.figma.com&#47;api&#47;oembed?url=https:&#47;&#47;www.figma.com&#47;proto&#47;cmBOQvP4AafvYuiRX3fFtq&#47;SISTEMA-DE-GESTI%25C3%2593N-DE-RESIDUOS?node-id=50-144&amp;node-type=canvas&amp;t=gmGycp28Bd6yGgYZ-0&amp;scaling=scale-down&amp;content-scaling=fixed&amp;page-id=0%3A1&amp;starting-point-node-id=17%3A11&amp;hide-ui=1" title="OEmbed" />

          <script nonce="yWXUfCx7ZuDVE7AS4dNQnA==">
            function isSupportedBrowser() {
              const isCSSLayerSupported = CSSLayerBlockRule !== undefined

                const hasNavigator = true

              const checks = [
                isCSSLayerSupported,
                hasNavigator,
                window.WebGL2RenderingContext !== undefined,
                window.WeakRef !== undefined,
              ]
              // The browser is supported if all checks pass
              return checks.every(v => v)
            }

            if (!isSupportedBrowser()) {
              location.href = '/unsupported_browser'
            }
          </script>

      <link rel="preload" as="script" href="https:&#47;&#47;www.figma.com&#47;webpack-artifacts&#47;assets&#47;runtime~prototype_app-3f76c41a9b4b54ca.min.js.br" crossorigin="anonymous" nonce="yWXUfCx7ZuDVE7AS4dNQnA==" />
      <link rel="preload" as="script" href="https:&#47;&#47;www.figma.com&#47;webpack-artifacts&#47;assets&#47;vendor-core-68cf3be3dda5691a.min.js.br" crossorigin="anonymous" nonce="yWXUfCx7ZuDVE7AS4dNQnA==" />
      <link rel="preload" as="script" href="https:&#47;&#47;www.figma.com&#47;webpack-artifacts&#47;assets&#47;svg-85bb0323-bbd3927a2ea75b75.min.js.br" crossorigin="anonymous" nonce="yWXUfCx7ZuDVE7AS4dNQnA==" />
      <link rel="preload" as="script" href="https:&#47;&#47;www.figma.com&#47;webpack-artifacts&#47;assets&#47;svg-b6c1b0d0-b86bb3e99a82d3dd.min.js.br" crossorigin="anonymous" nonce="yWXUfCx7ZuDVE7AS4dNQnA==" />
      <link rel="preload" as="script" href="https:&#47;&#47;www.figma.com&#47;webpack-artifacts&#47;assets&#47;svg-f3b69257-89f5b3b677b664ed.min.js.br" crossorigin="anonymous" nonce="yWXUfCx7ZuDVE7AS4dNQnA==" />
      <link rel="preload" as="script" href="https:&#47;&#47;www.figma.com&#47;webpack-artifacts&#47;assets&#47;svg-75148b34-c4da02a4cb2e125d.min.js.br" crossorigin="anonymous" nonce="yWXUfCx7ZuDVE7AS4dNQnA==" />
      <link rel="preload" as="script" href="https:&#47;&#47;www.figma.com&#47;webpack-artifacts&#47;assets&#47;svg-2128ab14-d336de60f487f4d5.min.js.br" crossorigin="anonymous" nonce="yWXUfCx7ZuDVE7AS4dNQnA==" />
      <link rel="preload" as="script" href="https:&#47;&#47;www.figma.com&#47;webpack-artifacts&#47;assets&#47;svg-3049dab6-86eb6c355c3ff63b.min.js.br" crossorigin="anonymous" nonce="yWXUfCx7ZuDVE7AS4dNQnA==" />
      <link rel="preload" as="script" href="https:&#47;&#47;www.figma.com&#47;webpack-artifacts&#47;assets&#47;svg-254a7ca8-04d02c33f7e2f9fe.min.js.br" crossorigin="anonymous" nonce="yWXUfCx7ZuDVE7AS4dNQnA==" />
      <link rel="preload" as="script" href="https:&#47;&#47;www.figma.com&#47;webpack-artifacts&#47;assets&#47;svg-f3af8338-a934f75582edb64e.min.js.br" crossorigin="anonymous" nonce="yWXUfCx7ZuDVE7AS4dNQnA==" />
      <link rel="preload" as="script" href="https:&#47;&#47;www.figma.com&#47;webpack-artifacts&#47;assets&#47;svg-245f5024-760243fb495fe682.min.js.br" crossorigin="anonymous" nonce="yWXUfCx7ZuDVE7AS4dNQnA==" />
      <link rel="preload" as="script" href="https:&#47;&#47;www.figma.com&#47;webpack-artifacts&#47;assets&#47;svg-3d606be2-becce902d9f8d258.min.js.br" crossorigin="anonymous" nonce="yWXUfCx7ZuDVE7AS4dNQnA==" />
      <link rel="preload" as="script" href="https:&#47;&#47;www.figma.com&#47;webpack-artifacts&#47;assets&#47;svg-4167f7d1-bda919e30ee08887.min.js.br" crossorigin="anonymous" nonce="yWXUfCx7ZuDVE7AS4dNQnA==" />
      <link rel="preload" as="script" href="https:&#47;&#47;www.figma.com&#47;webpack-artifacts&#47;assets&#47;svg-230ef48a-85b65e8d2fd47274.min.js.br" crossorigin="anonymous" nonce="yWXUfCx7ZuDVE7AS4dNQnA==" />
      <link rel="preload" as="script" href="https:&#47;&#47;www.figma.com&#47;webpack-artifacts&#47;assets&#47;svg-17c40becff13789b.min.js.br" crossorigin="anonymous" nonce="yWXUfCx7ZuDVE7AS4dNQnA==" />
      <link rel="preload" as="script" href="https:&#47;&#47;www.figma.com&#47;webpack-artifacts&#47;assets&#47;cssbuilder-b4e44bae6656b9a5.min.js.br" crossorigin="anonymous" nonce="yWXUfCx7ZuDVE7AS4dNQnA==" />
      <link rel="preload" as="script" href="https:&#47;&#47;www.figma.com&#47;webpack-artifacts&#47;assets&#47;vendor-1074f8f176b7c4b3.min.js.br" crossorigin="anonymous" nonce="yWXUfCx7ZuDVE7AS4dNQnA==" />
      <link rel="preload" as="script" href="https:&#47;&#47;www.figma.com&#47;webpack-artifacts&#47;assets&#47;vendor-be421af15f7f03f2.min.js.br" crossorigin="anonymous" nonce="yWXUfCx7ZuDVE7AS4dNQnA==" />
      <link rel="preload" as="script" href="https:&#47;&#47;www.figma.com&#47;webpack-artifacts&#47;assets&#47;vendor-1747f0083cc5c874.min.js.br" crossorigin="anonymous" nonce="yWXUfCx7ZuDVE7AS4dNQnA==" />
      <link rel="preload" as="script" href="https:&#47;&#47;www.figma.com&#47;webpack-artifacts&#47;assets&#47;4772-443923bc3cfd702a.min.js.br" crossorigin="anonymous" nonce="yWXUfCx7ZuDVE7AS4dNQnA==" />
      <link rel="preload" as="script" href="https:&#47;&#47;www.figma.com&#47;webpack-artifacts&#47;assets&#47;4683-d4cb18fd59a17004.min.js.br" crossorigin="anonymous" nonce="yWXUfCx7ZuDVE7AS4dNQnA==" />
      <link rel="preload" as="script" href="https:&#47;&#47;www.figma.com&#47;webpack-artifacts&#47;assets&#47;8153-acd3d4d1a2f41cb5.min.js.br" crossorigin="anonymous" nonce="yWXUfCx7ZuDVE7AS4dNQnA==" />
      <link rel="preload" as="script" href="https:&#47;&#47;www.figma.com&#47;webpack-artifacts&#47;assets&#47;1345-c3fa466aca75d79b.min.js.br" crossorigin="anonymous" nonce="yWXUfCx7ZuDVE7AS4dNQnA==" />
      <link rel="preload" as="script" href="https:&#47;&#47;www.figma.com&#47;webpack-artifacts&#47;assets&#47;2676-422024d3ad85bca5.min.js.br" crossorigin="anonymous" nonce="yWXUfCx7ZuDVE7AS4dNQnA==" />
      <link rel="preload" as="script" href="https:&#47;&#47;www.figma.com&#47;webpack-artifacts&#47;assets&#47;prototype_app-8bd8d425659e1b5b.min.js.br" crossorigin="anonymous" nonce="yWXUfCx7ZuDVE7AS4dNQnA==" />

      <link rel="preload" as="script" href="https:&#47;&#47;www.figma.com&#47;webpack-artifacts&#47;assets&#47;autosave-301d157d4266ff16.min.js.br" crossorigin="anonymous" nonce="yWXUfCx7ZuDVE7AS4dNQnA==" />





   <script nonce="yWXUfCx7ZuDVE7AS4dNQnA==">
Object.assign(window, JSON.parse(document.querySelector('[data-initial]').textContent));

console.log('Running frontend commit', "3b2b8b313c7c6b50d989f27a06377df9029f0361");

</script>

  <script nonce="yWXUfCx7ZuDVE7AS4dNQnA==">
    
!function(){try{var e="undefined"!=typeof window?window:"undefined"!=typeof global?global:"undefined"!=typeof self?self:{},n=(new Error).stack;n&&(e._sentryDebugIds=e._sentryDebugIds||{},e._sentryDebugIds[n]="79230df8-7cd7-5eb2-b72e-cdf397c0176d")}catch(e){}}();
(()=>{"use strict";class e extends WebSocket{constructor(e,t,o){super(e,t),this.onCloseCb=o,this.events=[],this._onopen_=null,this._onmessage_=null,this._onclose_=null,this._onerror_=null,super.onopen=this.onOpen,super.onmessage=this.onMessage,super.onclose=this.onClose,super.onerror=this.onError}onOpen(e){this.events.push({event:"onopen",ev:e}),this.flushIfInitialized()}onMessage(e){this.events.push({event:"onmessage",ev:e}),this.flushIfInitialized()}onClose(e){this.onCloseCb?.(),this.events.push({event:"onclose",ev:e}),this.flushIfInitialized()}onError(e){this.events.push({event:"onerror",ev:e}),this.flushIfInitialized()}flushIfInitialized(){if(this._onmessage_&&this._onopen_&&this._onclose_&&this._onerror_)for(;this.events.length>0;){let{event:e,ev:t}=this.events.shift();switch(e){case"onopen":this._onopen_(t);break;case"onmessage":this._onmessage_(t);break;case"onclose":this._onclose_(t);break;case"onerror":this._onerror_(t)}}}set onopen(e){this._onopen_=e,this.flushIfInitialized()}get onopen(){return this._onopen_}set onmessage(e){this._onmessage_=e,this.flushIfInitialized()}get onmessage(){return this._onmessage_}set onclose(e){this._onclose_=e,this.flushIfInitialized()}get onclose(){return this._onclose_}set onerror(e){this._onerror_=e,this.flushIfInitialized()}get onerror(){return this._onerror_}}let t=window.matchMedia("(prefers-color-scheme: dark)");function o(e){return"system"===e?t.matches?"dark":"light":"dark"===e?"dark":"light"}self.global=self;let n=(e,t,o,n,i,s)=>{if(e)window.userStateXHR={readyState:4,status:200,responseText:e};else if(window.Fig){if(n||!window.INITIAL_OPTIONS.user_data){window.startUserStateXHR=()=>{};return}window.startUserStateXHR=function(e){let t=i;if(!t){t="/api/user/state";var n=[];window.INITIAL_OPTIONS.org_id&&n.push("org_id="+window.INITIAL_OPTIONS.org_id),window.INITIAL_OPTIONS.team_id&&n.push("team_id="+window.INITIAL_OPTIONS.team_id),o&&n.push("omit_core_data=1"),e&&n.push("file_key="+e),0!==n.length&&(t+="?"+n.join("&"))}window.userStateXHR=new XMLHttpRequest,window.userStateXHR.open("GET",t);let r=window.INITIAL_OPTIONS.user_data?.id;r&&window.userStateXHR.setRequestHeader("X-Figma-User-ID",r),window.userStateXHR.send();var a=window.performance?window.performance.now():-1;window.userStateXHR.addEventListener("load",function(){window.userStateXHRDuration=window.performance?window.performance.now()-a:-1},!1),window.sessionStateXHR=new XMLHttpRequest,window.sessionStateXHR.open("GET",s||"/api/session/state"),r&&window.sessionStateXHR.setRequestHeader("X-Figma-User-ID",r),window.sessionStateXHR.send()};let e="/preload-editor"===location.pathname||"/preload-android-proto"===location.pathname||"/file/new"===location.pathname||"/design/new"===location.pathname||"/slides/new"===location.pathname||"/board/new"===location.pathname,r=window.INITIAL_OPTIONS.editing_file&&window.INITIAL_OPTIONS.editing_file.key;t?window.startUserStateXHR(r):e||window.startUserStateXHR()}};function i(e){return"dark"===e?"1E1E1E":"F5F5F5"}function s(){let e=null;try{e=window.localStorage}catch(e){}return e}let r="global-debug-theme-preference";function a(e){return e?e?.getItem(r)||"system":null}let l="chunked-file-load",d=(e,n)=>{let s=window.INITIAL_OPTIONS.user_data?.id,d=window.INITIAL_OPTIONS.tracking_session_id,c=window.INITIAL_OPTIONS.release_manifest_git_commit,w=null;null!=window.__figmaDesktop?w=window.__figmaDesktop.clientID??null:null!=window.__figmaDesktopGetPopoutAPI&&(w=window.__figmaDesktopGetPopoutAPI().clientID??null),window.mpGlobal={version:function(){if(!window.INITIAL_OPTIONS?.feature_flags?.manifest_commit_sha)return 129;let e=window.INITIAL_OPTIONS?.cluster_name;if("staging"!==e&&"local"!==e)return 129;let t=window.location.search;if(t.includes("force-client-version")){let e=new URLSearchParams(t).get("force-client-version");if(e){let t=parseInt(e);if(!isNaN(t)&&t>0)return console.log(`!! Overriding client version to ${t}`),t}}return 129}(),sock:null,msgs:[],perfMetrics:[],shouldConnectToMultiplayer:e,url({fileKey:t,role:o,oauthToken:i,nodeIds:r,initialBgColor:a,suppressDecodeErrors:I,connectionType:_,tagForLogging:p,forceViewOnly:h,canvasQuerySkipContainers:u}){if(!e)return"";let f=null;n&&t===n.fileKey&&n.targetFileVersion&&(f=n.targetFileVersion);let g="";("editor"===o||"viewerWithCpp"===o)&&r&&(g+=`&scenegraph-queries-initial-nodes=${r}`);let m=new URLSearchParams(window.location.search),O="true"===m.get("recovery"),T="true"===m.get("merge-on-file-open");"editor"!==o||n?.forceIncrementalForEditors!==1||O||T?(n?.forceIncrementalForEditors===0||O)&&(g+="&use-incremental-for-editors=0"):g+="&use-incremental-for-editors=1","editor"===o&&(window.INITIAL_OPTIONS.feature_flags?.incremental_loading_validation||T&&window.INITIAL_OPTIONS.feature_flags?.incremental_loading_validation_branching)&&(g+="&incremental-loading-validation=1");let N=1;try{let e=JSON.parse(sessionStorage.getItem("reload_times")||"[0]"),t=e[e.length-1];N=Date.now()-t<5e3?1:0}catch(e){}"editor"===o&&window.INITIAL_OPTIONS.feature_flags?.send_initial_bg_color||(a="");let S=u;("prototype"===o||"viewer"===o)&&(S=!0);let L=window.INITIAL_OPTIONS.feature_flags?.chunked_file_load&&"initial-load"===_,v=window.INITIAL_OPTIONS.e2e_traffic,P=window.INITIAL_OPTIONS.e2e_test_name;return`${location.protocol.replace("http","ws")}//${location.host}/api/multiplayer/${t}?role=${o}&tracking_session_id=${d}&version=${this.version}&recentReload=${N}&file-load-streaming-compression`+g+(i?"&oauth_token="+i:"")+(s?`&user-id=${s}`:"")+(f?`&target-file-version=${f}`:"")+(c?`&client_release=${c}`:"")+(a?`&initial-bg-color=${a}`:"")+(I?"&suppress-decode-errors":"")+(L?`&${l}`:"")+(L?"&chunk-size=5000":"")+(p?`&tag-for-logging=${p}`:"")+(v?"&e2e_traffic=true":"")+(P?`&e2e_test_name=${P}`:"")+(h?"&force-view-only":"")+(w?`&clientID=${w}`:"")+(S?"&canvas-query-skip-containers":"")},DEBUG_THEME_PREFERENCE_KEY:r,DARK_THEME_MEDIA_QUERY:t,themePreferenceFromLocalStorage:a,getBackgroundColorForTheme:i,getVisibleTheme:o,REQUEST_CHUNKED_FILE_LOAD_PARAM:l,preconnect(t){if(!1!==e){if(this.sock){if(t===this.sock.url&&this.sock.readyState!==WebSocket.CLOSED)return;try{this.sock.close()}catch(e){}}this.sock=new WebSocket(t),this.sock.binaryType="arraybuffer",this.sock.onopen=e=>{this.perfMetrics.push({key:"mp-ws-onopen",ts:performance.now(),nBytes:void 0})},this.sock.onmessage=e=>{let t=new Uint8Array(e.data);this.msgs.push(t),this.perfMetrics.push({key:"mp-ws-onmessage",ts:performance.now(),nBytes:t.length*t.BYTES_PER_ELEMENT})},this.msgs=[],this.perfMetrics=[]}}},n&&mpGlobal.preconnect(mpGlobal.url(n))},c=e=>{let t=()=>{let e=document.createElement("script");return e.type="text/javascript",e.async=!0,e.setAttribute("nonce",window.INITIAL_OPTIONS.csp_nonce),e.crossOrigin="anonymous",e},o=new Promise((o,n)=>{let i=t();i.onload=o,i.src=e,document.head.appendChild(i)});return o.catch(t=>console.error(`Fetching ${e} failed: ${t}`)),o};(()=>{let{file_minimal_user_state:t,mock_user_state_for_tests_json:r,multiplayer_preconnect_options:l,omit_core_data:w,omit_user_state:I,preload_fullscreen_urls:_,should_connect_to_multiplayer:p,api_user_state_path:h,api_session_state_path:u,skip_lg_preload:f}=window.EARLY_ARGS||{};if(window.INITIAL_OPTIONS||(window.INITIAL_OPTIONS={}),n(r,!!t,!!w,!!I,h,u),!/iPhone|iPad|iPod/.test(navigator.userAgent)){let t=window.INITIAL_OPTIONS?.feature_flags?.livegraph_connect_next,o=new URLSearchParams(window.INITIAL_OPTIONS?.page_load_token);o.append("userId",window.INITIAL_OPTIONS?.user_data?.id||""),o.append("anonUserId",window.INITIAL_OPTIONS?.anonymous_user_id||"");let n=!!(window.__figmaDesktop||window.__figmaDesktopGetPopoutAPI);o.append("clientType",n?"desktop":"web"),o.append("clientUrl",document.URL),o.append("commitHash",window.INITIAL_OPTIONS?.release_manifest_git_commit||"missing");let i=window.INITIAL_OPTIONS?.livegraph_preload_views||{};o.append("preload",JSON.stringify(i));let s=function(e,t,o){let n,i;if(e)try{let t=new URL(e);i=t.protocol,n=t.host}catch(e){}return(void 0===n||void 0===i)&&("admin.staging.figma.com"===(n=location.host)||"embed.staging.figma.com"===n?n="staging.figma.com":("admin.figma.com"===n||"embed.figma.com"===n)&&(n="www.figma.com"),i=location.protocol),`${"https:"===i?"wss":"ws"}://${n}${t?"/api/livegraph-next":"/api/livegraph"}?${o}`}(window.INITIAL_OPTIONS?.figma_url,!!t,o.toString()??"");f||(window.LGEarlyWS=new e(s,void 0,()=>{window.LGEarlyWS=void 0}))}if(l&&(l.initialBgColor=window.INITIAL_OPTIONS.feature_flags?.send_initial_bg_color?i(o(a(s()))):"",l.connectionType="initial-load",l.forceViewOnly=!1,(window.INITIAL_OPTIONS?.cluster_name==="staging"||window.INITIAL_OPTIONS?.cluster_name==="local")&&s()?.getItem("force-vscode")?l.forceViewOnly=!0:l.forceViewOnly=window?.location.ancestorOrigins&&[...window.location.ancestorOrigins].some(e=>e.startsWith("vscode-webview://"))),d(!1!==p,l),!_&&!/FigmaMobile-Android/.test(navigator.userAgent)&&(l?.role==="editor"||l?.role==="viewerWithCpp"||l?.role==="prototype")){let e=l?.role==="prototype"?Fig.prototypeLibURLs:Fig.fullscreenURLs,t=fetch(e["compiled_wasm.wasm"]);t.catch(e=>console.error(`Fetching compiled_wasm.wasm failed: ${e}`));let o=c(e["compiled_wasm.js"]);window.FULLSCREEN_PRELOADS={wasm:t,js:o}}})()})();

//# debugId=79230df8-7cd7-5eb2-b72e-cdf397c0176d

//# sourceMappingURL=https://admin.figma.com/admin/webpack-artifacts/079bf82841f2426b569976caa373c3c24f6e4c53/early-c010e2bf2b1123de.min.js.map
  </script>



    <meta name="google" content="notranslate" />
    <meta name="slack-app-id" content="A01N2QYSA81">

    <title>Figma</title>

    <style nonce="yWXUfCx7ZuDVE7AS4dNQnA==" type="text/css">

  /* This should be kept in sync with the $gridTileMinWidth CSS variable */
  :root {
    --file-grid-tile-min-width: 272px;
  }

  #filebrowser-loading-page {
    opacity: 1;
    -webkit-transition: opacity .2s ease-in-out;
  }

  .filebrowser-loading-page-layout {
    display: flex;
    flex-wrap: wrap;

    /* Make sure the loading page is flush with the edges of the page so
       our layout isnt affected by browser default margins/paddings */
    position: absolute;
    top: 48px;
    bottom: 0;
    left: 0;
    right: 0;
    background-color: var(--color-bg, var(--fallback-color-bg, white));
  }

  #loading-content-pane {
    opacity: 1;
    -webkit-transition: opacity .4s ease-in-out;
  }

  #filebrowser-loading-page.fadeOut {
    opacity: 0;
  }

  #filebrowser-loading-page.hidden {
    display: none;
    opacity: 0;
  }

  .filebrowser-loading-page .file-grid.create-file-grid {
    margin: 24px 0px;
    grid-gap: 32px;
    background-color: var(--color-bg, white);
  }

  /* HAX: see loading-page-container in loading_spinner.tsx */
  #loading-page-container .create-file-grid {
    display: none;
    background-color: var(--color-bg, white);
  }
  #loading-page-container .sort-dropdown {
    margin-top: 0px;
  }

 /*
  * HAX: The sidebar is cloned and used independently outside of this
  * page so any styles like `.filebrowser-loading-page .thing` applied
  * to sidebar sub-elements also need a selector like
  * `.filebrowser-loading-sidebar .thing` so that they work outside of
  * this page too.
  */
  .filebrowser-loading-page .row,
  .filebrowser-loading-sidebar .row {
    background-color: var(--color-bg-secondary, #f0f0f0);
    border-radius: 3px;
    height: 16px;
  }

  .filebrowser-loading-page .circle,
  .filebrowser-loading-sidebar .circle {
    border-radius: 3px;
    background-color: var(--color-bg-secondary, #f0f0f0);
    width: 16px;
    height: 16px;
  }

  .filebrowser-loading-page .row .circle,
  .filebrowser-loading-sidebar .row .circle {
    position: relative;
    top: -1px;
    left: -35px;
  }

  .filebrowser-loading-sidebar {
    flex: 0 0 240px;
    width: 240px;
    background-color: var(--color-bg, white);
    padding-top: 16px;
    display: flex;
    flex-direction: column;
  }

  .filebrowser-loading-page .navbar {
    height: 48px;
    width: 100%;
    position: fixed;
    top: 0;
    background-color: var(--color-bg-toolbar, #2C2C2C);
    z-index: 1;
  }

  .filebrowser-loading-sidebar .row {
    width: 85px;
    margin-top: 8px;
    margin-bottom: 12px;
    margin-left: 48px;
  }

  .filebrowser-loading-sidebar .row .circle {
    position: relative;
    top: -1px;
    left: -35px;
  }

  .filebrowser-loading-page .divider,
  .filebrowser-loading-sidebar .divider {
    height: 1px;
    background-color: var(--color-border, rgba(0, 0, 0, 0.1));
    margin-top: 8px;
    margin-bottom: 16px;
    margin-left: 16px;
    margin-right: 16px;
  }

  .filebrowser-loading-sidebar .row:nth-child(7) { width: 40px; }
  .filebrowser-loading-sidebar .row:nth-child(8) { width: 58px; }

  .filebrowser-loading-sidebar .row:nth-last-child(1) { opacity: 0.4; width: 65px; }
  .filebrowser-loading-sidebar .row:nth-last-child(2) { opacity: 0.4; width: 65px; }
  .filebrowser-loading-sidebar .row:nth-last-child(3) { opacity: 0.8; width: 46px; }

  .filebrowser-loading-page .page {
    flex: 1 1;
    box-sizing: border-box;
    border-left: 1px var(--color-border, #e5e5e5) solid;
    display: flex;
    flex-direction: column;
  }

  .filebrowser-loading-page .toolbar {
    border-bottom: 1px var(--color-border, #e5e5e5) solid;
    height: 48px;
  }

  .filebrowser-loading-page .toolbar .item {
    background-color: var(--color-bg-secondary, #f0f0f0);
    border-radius: 3px;
    width: 85px;
    height: 16px;
    margin-left: 32px;
    margin-top: 16px;
  }

  .filebrowser-loading-page .columns {
    flex: 1 1;
    display: flex;
    flex-direction: row-reverse;
    padding-right: 32px;
  }

  @media (max-width: 849px) {
    .filebrowser-loading-page .columns {
      flex-direction: column;
    }

    .filebrowser-loading-page .right-column {
      padding-left: 32px;
    }

    .filebrowser-loading-page .public-header + .columns {
      flex-direction: column-reverse;
    }
  }

  .filebrowser-loading-page .content {
    flex: 1 1;
  }

  .filebrowser-loading-page .sort-dropdown {
    border-radius: 3px;
    width: 86px;
    padding: 16px 32px 32px 32px;
  }

  .filebrowser-loading-page .create-file-tile {
    background-color: var(--color-bg-secondary, white);
    border: 1px solid var(--color-border, #e5e5e5);
    border-radius: 6px;
    display: flex;
    align-items: center;
    height: 72px;
    box-sizing: border-box;
  }

  @media (max-width: 832px) {
    .filebrowser-loading-page .create-file-tile {
      height: 48px;
    }
  }

  @media (max-width: 645px) {
    .filebrowser-loading-page .create-file-tile, .filebrowser-loading-page .sort-dropdown {
      display: none;
    }
  }

  .filebrowser-loading-page .create-file-tile .icon {
    background-color: var(--color-bg-secondary, #f0f0f0);
    border-radius: 2px;
    margin-left: 16px;
    margin-right: 16px;
    height: 24px;
    width: 24px;
  }

  .filebrowser-loading-page .create-file-tile .label {
    background-color: var(--color-bg-secondary, #f0f0f0);
    width: 132px;
    height: 16px;
    border-radius: 3px;
  }

  @media (max-width: 1440px) {
   .filebrowser-loading-page .create-file-tile:nth-last-child(1) {
     display: none;
   }
  }

  .filebrowser-loading-page .tile {
    height: 56px;
    padding-top: 60%;
    position: relative;
  }

  .filebrowser-loading-page .tile .inner {
    position: absolute;
    top: 2px;
    bottom: 2px;
    left: 2px;
    right: 2px;
    border: 1px solid var(--color-border, #e5e5e5);
    border-radius: 6px;
    background-color: var(--color-bg-secondary, #f0f0f0);
  }

  .filebrowser-loading-page .tile .inner .lower {
    height: 56px;
    background-color: var(--color-bg, white);
    position: absolute;
    bottom: 0;
    width: 100%;
    border-radius: 0 0 6px 6px;
  }

  .filebrowser-loading-page .public-grid {
    width: 100%;
    box-sizing: border-box;
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(var(--file-grid-tile-min-width), 1fr));
    grid-gap: 32px;
    padding-left: 32px;
  }

  @media (max-width: 1023px) {
    .filebrowser-loading-page .public-grid {
      grid-template-columns: 1fr;
    }
  }

  .filebrowser-loading-page .public-grid .tile {
    height: 56px;
    padding-top: 60%;
  }

  .filebrowser-loading-page .public-grid .tile:nth-child(6) { opacity: .8; }
  .filebrowser-loading-page .public-grid .tile:nth-child(7) { opacity: .4; }

  .filebrowser-loading-page .file-grid {
    width: 100%;
    box-sizing: border-box;
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(var(--file-grid-tile-min-width), 1fr));
    grid-gap: 32px;
    padding-left: 32px;
  }

  .filebrowser-loading-page .file-grid .tile:nth-child(6) { opacity: .8; }
  .filebrowser-loading-page .file-grid .tile:nth-child(7) { opacity: .4; }

  .filebrowser-loading-page .team-grid {
    width: 100%;
    box-sizing: border-box;
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(264px, 1fr));
    grid-gap: 32px 32px;
    padding: 32px 0 0 32px;
    align-content: start;
  }

  .filebrowser-loading-page .team-tile {
    border: 1px solid var(--color-border, rgba(0, 0, 0, .1));
    border-radius: 6px;
    position: relative;
    padding: 16px;
  }

  .filebrowser-loading-page .team-grid .team-tile:nth-child(6) { opacity: .8; }
  .filebrowser-loading-page .team-grid .team-tile:nth-child(7) { opacity: .4; }

  .filebrowser-loading-page .team-tile .row {
    margin-top: 0;
    margin-left: 0;
    margin-bottom: 0;
  }

  .filebrowser-loading-page .team-tile .row:nth-child(1) {
    width: 32px;
    height: 32px;
  }

  .filebrowser-loading-page .team-tile .row:nth-child(2) {
    width: 65px;
    height: 30px;
    position: absolute;
    top: 17px;
    right: 16px;
    margin-top: 0;
  }

  .filebrowser-loading-page .team-tile .row:nth-child(3) {
    width: 120px;
    margin-top: 20px;
  }
  .filebrowser-loading-page .team-tile .row:nth-child(4) {
    width: 232px;
    margin-top: 12px;
  }
  .filebrowser-loading-page .team-tile .row:nth-child(5) {
    width: 174px;
    margin-top: 8px;
  }

  .filebrowser-loading-page .team-tile .circles {
    display: flex;
    flex-direction: row;
  }

  .filebrowser-loading-page .team-tile .circle {
    top: 0;
    left: 0;
    width: 24px;
    height: 24px;
    margin-right: 8px;
    margin-top: 22px;
  }

  .filebrowser-loading-page .public-header {
    background-color: var(--color-bg-secondary, #f0f0f0);
    width: 100%;
    height: 240px;
    margin-bottom: 80px;
  }

  .filebrowser-loading-page .profile-header {
    background-color: var(--color-bg-secondary, #f0f0f0);
    width: 100%;
    height: 64px;
  }

  .filebrowser-loading-page .profile-grid {
    padding: 32px;
    display: grid;
    grid-template-columns: 1fr 24px 1fr .75fr;
    align-items: end;
  }

  .filebrowser-loading-page .profile-grid .row {
    margin-top: 24px;
  }

  .filebrowser-loading-page .profile-grid div:nth-child(4n+1) { width: 148px; }
  .filebrowser-loading-page .profile-grid div:nth-child(4n+3) { width: 56px; }
  .filebrowser-loading-page .profile-grid div:nth-child(4n+4) { width: 99px; }

  .filebrowser-loading-page .profile-grid div:nth-child(1) { width: 61px; margin-top: 0; }

  .filebrowser-loading-page .profile-grid div:nth-child(5) { width: 61px; margin-top: 32px; }
  .filebrowser-loading-page .profile-grid div:nth-child(7) { width: 69px; }
  .filebrowser-loading-page .profile-grid div:nth-child(8) { width: 51px; }

  .filebrowser-loading-page .profile-grid div:nth-child(9) { margin-top: 36px; }
  .filebrowser-loading-page .profile-grid div:nth-child(11) { width: 69px; }
  .filebrowser-loading-page .profile-grid div:nth-child(12) { width: 72px; }

  .filebrowser-loading-page .profile-grid div:nth-child(25),
  .filebrowser-loading-page .profile-grid div:nth-child(27),
  .filebrowser-loading-page .profile-grid div:nth-child(28) { opacity: .8; }

  .filebrowser-loading-page .profile-grid div:nth-child(29),
  .filebrowser-loading-page .profile-grid div:nth-child(31),
  .filebrowser-loading-page .profile-grid div:nth-child(32) { opacity: .4; }

  @media(max-width: 1000px) {
    .filebrowser-loading-page .profile-grid {
      grid-template-columns: 1fr;
    }

    .filebrowser-loading-page .profile-grid div:nth-child(5),
    .filebrowser-loading-page .profile-grid div:nth-child(6),
    .filebrowser-loading-page .profile-grid div:nth-child(7),
    .filebrowser-loading-page .profile-grid div:nth-child(8),
    .filebrowser-loading-page .profile-grid div:nth-child(4n+2),
    .filebrowser-loading-page .profile-grid div:nth-child(4n+3),
    .filebrowser-loading-page .profile-grid div:nth-child(4n+4) { display: none; }
  }

  .filebrowser-loading-page .project-grid {
    padding-left: 32px;
    display: grid;
    grid-row-gap: 22px;
  }

  .filebrowser-loading-page .project-grid .card {
    border: 1px solid var(--color-border, rgba(0, 0, 0, .1));
    border-radius: 4px;
    box-sizing: border-box;
    height: 178px;
    display: flex;
  }

  .filebrowser-loading-page .project-grid .card:nth-child(3) { opacity: .8; }
  .filebrowser-loading-page .project-grid .card:nth-child(4) { opacity: .4; }

  .filebrowser-loading-page .project-grid .card .left {
    width: 196px;
    margin: 16px;
  }

  .filebrowser-loading-page .project-grid .card .right {
    flex: 1 1;
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    overflow: hidden;
    margin: 16px 0;
  }

  .filebrowser-loading-page .project-grid .card .left .row:nth-child(1) { width: 107px; }
  .filebrowser-loading-page .project-grid .card .left .row:nth-child(2) { width: 164px; margin-top: 12px; }
  .filebrowser-loading-page .project-grid .card .left .row:nth-child(3) { width: 145px; margin-top: 8px; }
  .filebrowser-loading-page .project-grid .card .left .row:nth-child(4) { width: 158px; margin-top: 8px; }

  .filebrowser-loading-page .project-grid .card .right .row {
    height: 100%;
    flex: 1 1 196px;
    margin-right: 16px;
    border-radius: 6px;
  }

  .filebrowser-loading-page .right-column {
    flex: 0 0 304px;
    margin-right: 16px;
    margin-top: 16px;
    box-sizing: border-box;
    padding-left: 32px;
  }

  .filebrowser-loading-page .right-column .row:nth-child(1) {
    margin-top: 16px;
    width: 120px;
  }
  .filebrowser-loading-page .right-column .row:nth-child(2) {
    margin-top: 18px;
    width: 272px;
  }
  .filebrowser-loading-page .right-column .row:nth-child(3) {
    margin-top: 8px;
    width: 248px;
  }
  .filebrowser-loading-page .right-column .row:nth-child(4) {
    margin-top: 8px;
    width: 272px;
  }
  .filebrowser-loading-page .right-column .row:nth-child(5) {
    margin-top: 8px;
    width: 256px;
  }
  .filebrowser-loading-page .right-column .row:nth-child(6) {
    margin-top: 8px;
    width: 200px;
  }
  .filebrowser-loading-page .right-column .row:nth-child(7) {
    margin-top: 35px;
    width: 88px;
  }
  .filebrowser-loading-page .right-column .row:nth-child(8) {
    margin-top: 22px;
    margin-left: 51px;
    width: 88px;
    opacity: .8;
  }
  .filebrowser-loading-page .right-column .row:nth-child(9) {
    margin-top: 18px;
    margin-left: 51px;
    width: 88px;
    opacity: .4;
  }

  .filebrowser-loading-page .public-left-column {
    padding: 0 0 32px 32px;
    width: 320px;
  }

  .filebrowser-loading-page .public-left-column .row {
    margin-top: 8px;
  }

  .filebrowser-loading-page .public-left-column .row:nth-child(1) {
    width: 120px;
    margin-top: 0;
  }
  .filebrowser-loading-page .public-left-column .row:nth-child(2) {
    width: 272px;
    margin-top: 18px;
  }
  .filebrowser-loading-page .public-left-column .row:nth-child(3) {
    width: 248px;
  }
  .filebrowser-loading-page .public-left-column .row:nth-child(4) {
    width: 272px;
  }
  .filebrowser-loading-page .public-left-column .row:nth-child(5) {
    width: 256px;
    opacity: .8;
  }
  .filebrowser-loading-page .public-left-column .row:nth-child(6) {
    width: 200px;
    opacity: .4;
  }

  /*
  Note: Make sure any changes here are also duplicated in the fullscreen progress bar
  (.progressBar in progress_bar.css)
  */
  #filebrowser-loading-progress-bar {
    height: 5px;
    /* Z index 6 chosen here so it renders over any nav elements but below any scroll bar or modals */
    z-index: 6;

      background: var(--color-bg-brand, #0D99FF);

    position: absolute;
    left: 0;
    animation: filebrowserloadingProgressBar 10s cubic-bezier(.08,.8,.1,1) forwards;
  }

  @keyframes filebrowserloadingProgressBar {
    from { width: 0; }
    to { width: 100%; }
  }


  @media (max-width: 645px) {
    .filebrowser-loading-sidebar {
      display: none;
    }

    .filebrowser-loading-page .page {
      margin-left: 0;
      width: 100%;
    }

    .filebrowser-loading-page .public-header {
      height: 120px;
    }

    .filebrowser-loading-page .file-grid {
      grid-template-columns: 1fr;
      max-width: 400px;
      margin: 0 auto;
      align-self: center;
    }
  }

</style>


    <style nonce="yWXUfCx7ZuDVE7AS4dNQnA==" type="text/css">

  /*  PAGE LAYOUT STYLES */
  .fb-page-layout {
    background-color: var(--color-bg, var(--fallback-color-bg, white));
  }

  .fb-flex-row {
    height: 100vh;
    display: flex;
    flex-direction: row;
  }

  .fb-sidebar {
    width: 264px;
    padding-top: 4px;
    display: flex;
    flex-direction: column;
  }

  .fb-sidebar > :nth-last-child(2) {
    opacity: 0.6;
  }

  .fb-sidebar > :nth-last-child(1) {
    opacity: 0.3;
  }

  .fb-page {
    display: flex;
    flex-direction: column;
    flex-grow: 1;
    border-left: 1px var(--color-border) solid;
  }

  .fb-page-content-columns {
    overflow: hidden;
    flex-grow: 1;
    display: flex;
    flex-direction: row;
  }

  .fb-page-content {
    flex-grow: 1;
    overflow: hidden;
    position: relative;
    margin-right: 32px;
  }

  .fb-page-right-column {
    width: 304px;
    margin-top: 24px;
    margin-right: 16px;
    padding-left: 32px;
  }

  .fb-fading-content {
    margin-left: 32px;
  }

  /* This is what applies the fading gradient over the skeletons */
  .fb-fading-content:after {
    position: absolute;
    bottom: 0;
    height: 100%;
    width: 100%;
    content: "";
    background: linear-gradient(to bottom, transparent 50%, var(--color-bg) 100%);
    pointer-events: none;
  }

  /* SIDEBAR STYLES */

  .fb-sidebar-account-and-notifications {
    padding: 8px 12px;
    display: flex;
    flex-direction: row;
    align-items: center;
    gap: 8px;
  }

  .fb-sidebar-searchbar {
    padding: 0 8px;
    margin-top: 4px;
    margin-bottom: 8px;
  }

  .fb-sidebar-row {
    padding: 8px 16px;
    display: flex;
    flex-direction: row;
    align-items: center;
  }

  .fb-sidebar-row :nth-child(2) {
    margin-left: 12px;
  }


  .fb-divider {
    height: 1px;
    background-color: var(--color-border, rgba(0, 0, 0, 0.1));
    width: 100%;
    margin-top: 8px;
    margin-bottom: 10px;
  }


  @media (max-width: 645px) {
    .fb-sidebar {
      display: none;
    }
  }

  /* RIGHT COLUMN STYLES */

  .fb-page-right-column-header {
    margin-bottom: 18px;
  }

  .fb-page-right-column-rows > :not(:first-child) {
    margin-top: 8px;
  }

  .fb-page-right-column-lower {
    margin-top: 35px;
  }

  .fb-page-right-column-user-list {
    margin-top: 22px;
    margin-left: 16px;
    display: flex;
    flex-direction: column;
    gap: 18px;
  }

  .fb-page-right-column-user {
    display: flex;
    flex-direction: row;
    gap: 16px;
  }

  .fb-page-right-column-user:nth-child(2) {
    opacity: 0.6;
  }

  .fb-page-right-column-user:nth-child(3) {
    opacity: 0.3;
  }

  /* Skeleton Item Styles */

  .fb-shrink-0 {
    flex-shrink: 0;
  }

  .fb-circle-16 {
    flex-shrink: 0;
    background-color: var(--color-bg-secondary, #f0f0f0);
    height: 16px;
    width: 16px;
    border-radius: 9999px;
  }

  .fb-circle-24 {
    background-color: var(--color-bg-secondary, #f0f0f0);
    height: 24px;
    width: 24px;
    border-radius: 9999px;
  }

  .fb-rectangle-16 {
    background-color: var(--color-bg-secondary);
    height: 16px;
    border-radius: 3px;
  }

  .fb-rectangle-24 {
    background-color: var(--color-bg-secondary);
    height: 24px;
    border-radius: 3px;
  }

  .fb-rectangle-32 {
    background-color: var(--color-bg-secondary);
    height: 32px;
    border-radius: 8px;
  }

  .fb-rectangle-36 {
    background-color: var(--color-bg-secondary);
    height: 36px;
    border-radius: 3px;
  }

  /* Skeleton Item Width Options */

  .fb-width-16 {
    width: 16px;
  }

  .fb-width-32 {
    width: 32px;
  }

  .fb-width-36 {
    width: 36px;
  }

  .fb-width-50 {
    width: 50px;
  }

  .fb-width-55 {
    width: 55px;
  }

  .fb-width-60 {
    width: 60px;
  }

  .fb-width-70 {
    width: 70px;
  }

  .fb-width-80 {
    width: 80px;
  }

  .fb-width-88 {
    width: 88px;
  }

  .fb-width-100 {
    width: 100px;
  }

  .fb-width-105 {
    width: 105px;
  }

  .fb-width-115 {
    width: 115px;
  }

  .fb-width-120 {
    width: 120px;
  }

  .fb-width-148 {
    width: 148px;
  }

  .fb-width-167 {
    width: 167px;
  }

  .fb-width-180 {
    width: 180px;
  }

  .fb-width-200 {
    width: 200px;
  }

  .fb-width-248 {
    width: 248px;
  }

  .fb-width-256 {
    width: 256px;
  }

  .fb-width-272 {
    width: 272px;
  }

  .fb-width-full {
    width: 100%;
  }

  /* Header Styles */

  .fb-toolbar-48 {
    border-bottom: 1px var(--color-border, #e5e5e5) solid;
    height: 48px;
    display: flex;
    flex-shrink: 0;
    align-items: center;
    padding-left: 32px;
  }

  .fb-toolbar-64 {
    border-bottom: 1px var(--color-border, #e5e5e5) solid;
    height: 64px;
    /* We have 10px above the toolbar in the actual page */
    margin-top: 10px;
    display: flex;
    flex-shrink: 0;
    align-items: center;
    padding-left: 32px;
  }

  .fb-toolbar-84 {
    border-bottom: 1px var(--color-border, #e5e5e5) solid;
    height: 80px;
    /* We have 4px above the toolbar in the actual page */
    margin-top: 4px;
    display: flex;
    flex-shrink: 0;
    align-items: center;
    padding-left: 32px;
  }

  .fb-toolbar-84 :nth-child(2) {
    margin-left: 12px;
  }

  .fb-breadcrumb {
    height: 48px;
    display: flex;
    flex-shrink: 0;
    align-items: center;
    padding-left: 32px;
  }

  .fb-header {
    height: 64px;
    display: flex;
    flex-shrink: 0;
    flex-direction: row;
    align-items: center;
    padding-left: 32px;
  }

  .fb-header :nth-child(2) {
    margin-left: 12px;
  }

  .fb-viewbar {
    padding-left: 32px;
    height: 64px;
    align-items: center;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
  }

  /* Page Content: Tile Grid */

  .fb-tile-grid {
    display: grid;
    gap: 32px;
    justify-items: stretch;
    /* Keep this grid template in line with the grid-template-columns in `file+browser/tile_grid/tile_grid.css` */
    grid-template-columns: repeat(auto-fill, minmax(264px, 1fr));
  }

  .fb-tile-grid-top-padding {
    margin-top: 24px;
  }

  .fb-file-tile {
    display: flex;
    flex-direction: column;
  }

  .fb-file-tile .fb-rectangle-16 {
    margin-top: 20px;
    margin-bottom: 20px
  }

  .fb-file-thumbnail {
    background-color: var(--color-bg-secondary);
    aspect-ratio: 16 / 9;
    border-radius: 8px;
  }

  .fb-project-tile {
    border: 1px solid var(--color-border);
    border-radius: 16px;
    display: flex;
    flex-direction: column;
    padding: 24px;
  }

  .fb-project-tile > :nth-child(2) {
    margin-top: 16px;
  }

  .fb-project-tile > :nth-child(3) {
    margin-top: 8px;
  }

  .fb-team-tile {
    border: 1px solid var(--color-border);
    border-radius: 16px;
    display: flex;
    flex-direction: column;
    padding: 24px;
  }

  .fb-team-tile > :nth-child(2) {
    margin-top: 48px;
  }

  .fb-team-tile > :nth-child(3),
  .fb-team-tile > :nth-child(4) {
    margin-top: 8px;
  }

  .fb-project-preview-grid {
    display: grid;
    gap: 12px;
    justify-items: stretch;
    grid-template-columns: 1fr 1fr;
  }

  @media (max-width: 645px) {

    .fb-tile-grid {
      grid-template-columns: 100%;
    }
  }

  .fb-profile-grid-header {
    margin-top: 24px;
    margin-bottom: 8px;
  }

  .fb-profile-grid {
    padding-top: 32px;
    display: grid;
    grid-template-columns: 1fr 1fr .75fr;
    grid-auto-rows: 40px;
  }

  .fb-profile-grid > :nth-last-child(1),
  .fb-profile-grid > :nth-last-child(2),
  .fb-profile-grid > :nth-last-child(3) {
    opacity: 0.3;
  }

  .fb-profile-grid > :nth-last-child(4),
  .fb-profile-grid > :nth-last-child(5),
  .fb-profile-grid > :nth-last-child(6) {
    opacity: 0.6;
  }

</style>


      <meta name="mobile-web-app-capable" content="yes">
      <meta name="apple-mobile-web-app-capable" content="yes">
      <meta name="apple-mobile-web-app-status-bar-style" content="black-translucent">
      <meta name="viewport" content="initial-scale=1.0, minimum-scale=1.0, maximum-scale=1.0, user-scalable=no">

      <meta name="apple-mobile-web-app-capable" content="yes">
      <meta property="og:title" content="Figma" />
    <meta property="og:site_name" content="Figma" />

        <meta http-equiv="origin-trial" content="AoQTPcuPlCSbjV10UH2WvK24oM6P8hPGU+mEqnmiheT3HoLFC+x7YTW/zq2tYuYfbVYWh/fpBcQTmGRJr80QOwkAAAB6eyJvcmlnaW4iOiJodHRwczovL3d3dy5maWdtYS5jb206NDQzIiwiZmVhdHVyZSI6IktleWJvYXJkRm9jdXNhYmxlU2Nyb2xsZXJzT3B0T3V0IiwiZXhwaXJ5IjoxNzQyMzQyMzk5LCJpc1N1YmRvbWFpbiI6dHJ1ZX0=">

    


<link rel="icon" sizes="192x192" href="https://static.figma.com/uploads/1a667ef53b7c4837049399d0593ffca39e0bec9e">
<link rel="icon" sizes="128x128" href="https://static.figma.com/uploads/b6df2735e4cb368306acf5480b50f96e69f96099">

<link rel="icon" type="image/png" href="https://static.figma.com/app/icon/1/favicon.png" />
<!--[if IE]><link rel="shortcut icon" href="https://static.figma.com/app/icon/1/favicon.ico" type="image/vnd.microsoft.icon" /><![endif]-->
<link rel="icon" sizes="any" type="image/svg+xml" href="https://static.figma.com/app/icon/1/favicon.svg">

<link rel="apple-touch-icon" sizes="76x76"   href="https://static.figma.com/app/icon/1/touch-76.png">
<link rel="apple-touch-icon" sizes="120x120" href="https://static.figma.com/app/icon/1/touch-120.png">
<link rel="apple-touch-icon" sizes="152x152" href="https://static.figma.com/app/icon/1/touch-152.png">
<link rel="apple-touch-icon" sizes="167x167" href="https://static.figma.com/app/icon/1/touch-167.png">
<link rel="apple-touch-icon" sizes="180x180" href="https://static.figma.com/app/icon/1/touch-180.png">




        <link rel="preload" href="https:&#47;&#47;static.figma.com&#47;uploads&#47;2cca21a49f7dad1daa612d73d50357644671964a" as="font" crossorigin="anonymous">
        <link rel="preload" href="https:&#47;&#47;static.figma.com&#47;uploads&#47;43d730c59dee2754d29e0d946ba8cb8339656979" as="font" crossorigin="anonymous">
        <link rel="preload" href="https:&#47;&#47;static.figma.com&#47;webfont&#47;1&#47;DSEG7Classic-Italic-Custom2.woff2" as="font" crossorigin="anonymous">

      <link href="https:&#47;&#47;www.figma.com&#47;webpack-artifacts&#47;assets&#47;prototype_app-30d1b54296c904f0.min.css.br" rel="stylesheet" crossorigin="anonymous">

      <link rel="preload" href="https:&#47;&#47;static.figma.com&#47;fullscreen&#47;412715a304fec6b519b02cfc4221ec361421d7d0&#47;mobile_viewer&#47;ts-viewer.js.br" as="script" crossorigin="anonymous" nonce="yWXUfCx7ZuDVE7AS4dNQnA==">
      <link rel="preload" as="fetch" id="englishDictionaryUrl" href="https:&#47;&#47;www.figma.com&#47;webpack-artifacts&#47;assets&#47;prototype_app-e8ded8ad2f0de170.min.en.json.br" crossorigin="anonymous" />
  </head>
  <body class="feature_flag_use_images_redis_cluster feature_flag_ds_gradient_variables feature_flag_piper feature_flag_file_browser_thumbnails_16_by_9 feature_flag_sc_update_folder_sa_disable_disable_lis feature_flag_sc_update_folder_sa_disable_dry_run feature_flag_qa_user_additional_feedback feature_flag_qa_v2_modality_management feature_flag_qa_universal_feedback_buttons feature_flag_unified_index_v3_modal_z feature_flag_dse_instance_swapper_ui3 feature_flag_figjam_locking_improvements feature_flag_dt_dev_variables_table feature_flag_user_settings_tab feature_flag_fpl_button_flex">
      <style nonce="yWXUfCx7ZuDVE7AS4dNQnA==">
       .preload-ui-fonts {
          position: fixed;
          top: -1000px;
          left: -1000px;
        }
      </style>
      <div class="preload-ui-fonts">
        <div aria-hidden="true" id="font-ui-400-normal">a</div>
        <div aria-hidden="true" id="font-ui-400-italic">a</div>
        <div aria-hidden="true" id="font-ui-500-normal">a</div>
        <div aria-hidden="true" id="font-ui-500-italic">a</div>
        <div aria-hidden="true" id="font-ui-600-normal">a</div>
        <div aria-hidden="true" id="font-ui-600-italic">a</div>

        <div aria-hidden="true" id="font-ui-400-normal-white">a</div>
      </div>


    <div id="react-page"></div>

      <script nonce="yWXUfCx7ZuDVE7AS4dNQnA==">
  const themePreference = window.localStorage.getItem('global-debug-theme-preference') || 'system'

  let theme
  if (themePreference === 'dark') {
    theme = 'dark'
  } else if (themePreference === 'system') {
    theme = window.matchMedia('(prefers-color-scheme: dark)').matches ? 'dark' : 'light'
  } else {
    theme = 'light'
  }

  document.querySelector("body").dataset.preferredTheme = theme
</script>



      <div class='file-browser-loading-page-container'>
  <div id="filebrowser-loading-page"
      class="fb-page-layout hidden fadeOut"
  >
    <div id="filebrowser-loading-progress-bar"></div>

  <div class="fb-flex-row">
    <div id="filebrowser-loading-sidebar" class="fb-sidebar">
      <div class="fb-sidebar-account-and-notifications">
        <div class="fb-circle-24 fb-shrink-0"></div>
        <div class="fb-rectangle-16 fb-width-120"></div>
      </div>
      <div class="fb-sidebar-searchbar">
        <div class="fb-rectangle-32 fb-width-full"></div>
      </div>
      <div class="fb-sidebar-row">
        <div class="fb-rectangle-16 fb-width-16 fb-shrink-0"></div>
        <div class="fb-rectangle-16 fb-width-70"></div>
      </div>
      <div class="fb-divider"></div>
      <div class="fb-sidebar-row">
        <div class="fb-circle-16"></div>
        <div class="fb-rectangle-16 fb-width-115"></div>
      </div>
      <div class="fb-sidebar-row">
        <div class="fb-rectangle-16 fb-width-16 fb-shrink-0"></div>
        <div class="fb-rectangle-16 fb-width-70"></div>
      </div>
      <div class="fb-sidebar-row">
        <div class="fb-rectangle-16 fb-width-16 fb-shrink-0"></div>
        <div class="fb-rectangle-16 fb-width-100"></div>
      </div>
      <div class="fb-sidebar-row">
        <div class="fb-rectangle-16 fb-width-60"></div>
      </div>
      <div class="fb-sidebar-row">
        <div class="fb-rectangle-16 fb-width-16 fb-shrink-0"></div>
        <div class="fb-rectangle-16 fb-width-100"></div>
      </div>
      <div class="fb-sidebar-row">
        <div class="fb-rectangle-16 fb-width-16 fb-shrink-0"></div>
        <div class="fb-rectangle-16 fb-width-80"></div>
      </div>
      <div class="fb-sidebar-row">
        <div class="fb-rectangle-16 fb-width-16 fb-shrink-0"></div>
        <div class="fb-rectangle-16 fb-width-120"></div>
      </div>
      <div class="fb-sidebar-row">
        <div class="fb-rectangle-16 fb-width-16 fb-shrink-0"></div>
        <div class="fb-rectangle-16 fb-width-105"></div>
      </div>
    </div>


    <div class="fb-page">


          <div class="fb-toolbar-48">
            <div class="fb-rectangle-16 fb-width-120"></div>
          </div>



      <div class="fb-page-content-columns">

        <div class="fb-page-content">

          <div id="loading-content-pane">
            <div class="fb-fading-content">


                  <div class="fb-tile-grid fb-tile-grid-top-padding">

                      <div class="fb-file-tile">
                        <div class="fb-file-thumbnail"></div>
                        <div class="fb-rectangle-16 fb-width-120"></div>
                      </div>
                      <div class="fb-file-tile">
                        <div class="fb-file-thumbnail"></div>
                        <div class="fb-rectangle-16 fb-width-120"></div>
                      </div>
                      <div class="fb-file-tile">
                        <div class="fb-file-thumbnail"></div>
                        <div class="fb-rectangle-16 fb-width-120"></div>
                      </div>
                      <div class="fb-file-tile">
                        <div class="fb-file-thumbnail"></div>
                        <div class="fb-rectangle-16 fb-width-120"></div>
                      </div>
                      <div class="fb-file-tile">
                        <div class="fb-file-thumbnail"></div>
                        <div class="fb-rectangle-16 fb-width-120"></div>
                      </div>
                      <div class="fb-file-tile">
                        <div class="fb-file-thumbnail"></div>
                        <div class="fb-rectangle-16 fb-width-120"></div>
                      </div>
                      <div class="fb-file-tile">
                        <div class="fb-file-thumbnail"></div>
                        <div class="fb-rectangle-16 fb-width-120"></div>
                      </div>
                      <div class="fb-file-tile">
                        <div class="fb-file-thumbnail"></div>
                        <div class="fb-rectangle-16 fb-width-120"></div>
                      </div>
                      <div class="fb-file-tile">
                        <div class="fb-file-thumbnail"></div>
                        <div class="fb-rectangle-16 fb-width-120"></div>
                      </div>
                      <div class="fb-file-tile">
                        <div class="fb-file-thumbnail"></div>
                        <div class="fb-rectangle-16 fb-width-120"></div>
                      </div>
                      <div class="fb-file-tile">
                        <div class="fb-file-thumbnail"></div>
                        <div class="fb-rectangle-16 fb-width-120"></div>
                      </div>
                      <div class="fb-file-tile">
                        <div class="fb-file-thumbnail"></div>
                        <div class="fb-rectangle-16 fb-width-120"></div>
                      </div>
                      <div class="fb-file-tile">
                        <div class="fb-file-thumbnail"></div>
                        <div class="fb-rectangle-16 fb-width-120"></div>
                      </div>
                      <div class="fb-file-tile">
                        <div class="fb-file-thumbnail"></div>
                        <div class="fb-rectangle-16 fb-width-120"></div>
                      </div>
                      <div class="fb-file-tile">
                        <div class="fb-file-thumbnail"></div>
                        <div class="fb-rectangle-16 fb-width-120"></div>
                      </div>
                      <div class="fb-file-tile">
                        <div class="fb-file-thumbnail"></div>
                        <div class="fb-rectangle-16 fb-width-120"></div>
                      </div>
                      <div class="fb-file-tile">
                        <div class="fb-file-thumbnail"></div>
                        <div class="fb-rectangle-16 fb-width-120"></div>
                      </div>
                      <div class="fb-file-tile">
                        <div class="fb-file-thumbnail"></div>
                        <div class="fb-rectangle-16 fb-width-120"></div>
                      </div>
                      <div class="fb-file-tile">
                        <div class="fb-file-thumbnail"></div>
                        <div class="fb-rectangle-16 fb-width-120"></div>
                      </div>
                      <div class="fb-file-tile">
                        <div class="fb-file-thumbnail"></div>
                        <div class="fb-rectangle-16 fb-width-120"></div>
                      </div>
                      <div class="fb-file-tile">
                        <div class="fb-file-thumbnail"></div>
                        <div class="fb-rectangle-16 fb-width-120"></div>
                      </div>
                  </div>

            </div>
          </div>
        </div>

        &nbsp;


      </div>
    </div>
  </div>
</div>




    <script nonce="yWXUfCx7ZuDVE7AS4dNQnA==" data-entrypoint="prototype_app">
      window.ENTRY_POINT = document.currentScript.dataset.entrypoint
    </script>

    

      <script nonce="yWXUfCx7ZuDVE7AS4dNQnA==">
    window['sentryConfig'] = {
      id: 1302143614040137592,
    }
  </script>


      <script nonce="yWXUfCx7ZuDVE7AS4dNQnA==" src="https:&#47;&#47;www.figma.com&#47;webpack-artifacts&#47;assets&#47;runtime~prototype_app-3f76c41a9b4b54ca.min.js.br" defer crossorigin="anonymous"></script>
      <script nonce="yWXUfCx7ZuDVE7AS4dNQnA==" src="https:&#47;&#47;www.figma.com&#47;webpack-artifacts&#47;assets&#47;vendor-core-68cf3be3dda5691a.min.js.br" defer crossorigin="anonymous"></script>
      <script nonce="yWXUfCx7ZuDVE7AS4dNQnA==" src="https:&#47;&#47;www.figma.com&#47;webpack-artifacts&#47;assets&#47;svg-85bb0323-bbd3927a2ea75b75.min.js.br" defer crossorigin="anonymous"></script>
      <script nonce="yWXUfCx7ZuDVE7AS4dNQnA==" src="https:&#47;&#47;www.figma.com&#47;webpack-artifacts&#47;assets&#47;svg-b6c1b0d0-b86bb3e99a82d3dd.min.js.br" defer crossorigin="anonymous"></script>
      <script nonce="yWXUfCx7ZuDVE7AS4dNQnA==" src="https:&#47;&#47;www.figma.com&#47;webpack-artifacts&#47;assets&#47;svg-f3b69257-89f5b3b677b664ed.min.js.br" defer crossorigin="anonymous"></script>
      <script nonce="yWXUfCx7ZuDVE7AS4dNQnA==" src="https:&#47;&#47;www.figma.com&#47;webpack-artifacts&#47;assets&#47;svg-75148b34-c4da02a4cb2e125d.min.js.br" defer crossorigin="anonymous"></script>
      <script nonce="yWXUfCx7ZuDVE7AS4dNQnA==" src="https:&#47;&#47;www.figma.com&#47;webpack-artifacts&#47;assets&#47;svg-2128ab14-d336de60f487f4d5.min.js.br" defer crossorigin="anonymous"></script>
      <script nonce="yWXUfCx7ZuDVE7AS4dNQnA==" src="https:&#47;&#47;www.figma.com&#47;webpack-artifacts&#47;assets&#47;svg-3049dab6-86eb6c355c3ff63b.min.js.br" defer crossorigin="anonymous"></script>
      <script nonce="yWXUfCx7ZuDVE7AS4dNQnA==" src="https:&#47;&#47;www.figma.com&#47;webpack-artifacts&#47;assets&#47;svg-254a7ca8-04d02c33f7e2f9fe.min.js.br" defer crossorigin="anonymous"></script>
      <script nonce="yWXUfCx7ZuDVE7AS4dNQnA==" src="https:&#47;&#47;www.figma.com&#47;webpack-artifacts&#47;assets&#47;svg-f3af8338-a934f75582edb64e.min.js.br" defer crossorigin="anonymous"></script>
      <script nonce="yWXUfCx7ZuDVE7AS4dNQnA==" src="https:&#47;&#47;www.figma.com&#47;webpack-artifacts&#47;assets&#47;svg-245f5024-760243fb495fe682.min.js.br" defer crossorigin="anonymous"></script>
      <script nonce="yWXUfCx7ZuDVE7AS4dNQnA==" src="https:&#47;&#47;www.figma.com&#47;webpack-artifacts&#47;assets&#47;svg-3d606be2-becce902d9f8d258.min.js.br" defer crossorigin="anonymous"></script>
      <script nonce="yWXUfCx7ZuDVE7AS4dNQnA==" src="https:&#47;&#47;www.figma.com&#47;webpack-artifacts&#47;assets&#47;svg-4167f7d1-bda919e30ee08887.min.js.br" defer crossorigin="anonymous"></script>
      <script nonce="yWXUfCx7ZuDVE7AS4dNQnA==" src="https:&#47;&#47;www.figma.com&#47;webpack-artifacts&#47;assets&#47;svg-230ef48a-85b65e8d2fd47274.min.js.br" defer crossorigin="anonymous"></script>
      <script nonce="yWXUfCx7ZuDVE7AS4dNQnA==" src="https:&#47;&#47;www.figma.com&#47;webpack-artifacts&#47;assets&#47;svg-17c40becff13789b.min.js.br" defer crossorigin="anonymous"></script>
      <script nonce="yWXUfCx7ZuDVE7AS4dNQnA==" src="https:&#47;&#47;www.figma.com&#47;webpack-artifacts&#47;assets&#47;cssbuilder-b4e44bae6656b9a5.min.js.br" defer crossorigin="anonymous"></script>
      <script nonce="yWXUfCx7ZuDVE7AS4dNQnA==" src="https:&#47;&#47;www.figma.com&#47;webpack-artifacts&#47;assets&#47;vendor-1074f8f176b7c4b3.min.js.br" defer crossorigin="anonymous"></script>
      <script nonce="yWXUfCx7ZuDVE7AS4dNQnA==" src="https:&#47;&#47;www.figma.com&#47;webpack-artifacts&#47;assets&#47;vendor-be421af15f7f03f2.min.js.br" defer crossorigin="anonymous"></script>
      <script nonce="yWXUfCx7ZuDVE7AS4dNQnA==" src="https:&#47;&#47;www.figma.com&#47;webpack-artifacts&#47;assets&#47;vendor-1747f0083cc5c874.min.js.br" defer crossorigin="anonymous"></script>
      <script nonce="yWXUfCx7ZuDVE7AS4dNQnA==" src="https:&#47;&#47;www.figma.com&#47;webpack-artifacts&#47;assets&#47;4772-443923bc3cfd702a.min.js.br" defer crossorigin="anonymous"></script>
      <script nonce="yWXUfCx7ZuDVE7AS4dNQnA==" src="https:&#47;&#47;www.figma.com&#47;webpack-artifacts&#47;assets&#47;4683-d4cb18fd59a17004.min.js.br" defer crossorigin="anonymous"></script>
      <script nonce="yWXUfCx7ZuDVE7AS4dNQnA==" src="https:&#47;&#47;www.figma.com&#47;webpack-artifacts&#47;assets&#47;8153-acd3d4d1a2f41cb5.min.js.br" defer crossorigin="anonymous"></script>
      <script nonce="yWXUfCx7ZuDVE7AS4dNQnA==" src="https:&#47;&#47;www.figma.com&#47;webpack-artifacts&#47;assets&#47;1345-c3fa466aca75d79b.min.js.br" defer crossorigin="anonymous"></script>
      <script nonce="yWXUfCx7ZuDVE7AS4dNQnA==" src="https:&#47;&#47;www.figma.com&#47;webpack-artifacts&#47;assets&#47;2676-422024d3ad85bca5.min.js.br" defer crossorigin="anonymous"></script>
      <script nonce="yWXUfCx7ZuDVE7AS4dNQnA==" src="https:&#47;&#47;www.figma.com&#47;webpack-artifacts&#47;assets&#47;prototype_app-8bd8d425659e1b5b.min.js.br" defer crossorigin="anonymous"></script>

      <script nonce="yWXUfCx7ZuDVE7AS4dNQnA==" src="https:&#47;&#47;www.figma.com&#47;webpack-artifacts&#47;assets&#47;autosave-301d157d4266ff16.min.js.br" defer crossorigin="anonymous"></script>
  </body>
</html>











-----------------------------//----------------------ading FASE4_GestiónResiduos_HTML_EF.txt…]()



[deepseek_html_20261112_38edfc.html](https://github.com/user-attachments/files/34738226/deepseek_html_20261112_38edfc.html)
<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Vkontakte Visual</title>
<style>
*{margin:0;padding:0;box-sizing:border-box;-webkit-tap-highlight-color:transparent}
:root{--bg:#000;--surface:#0b0b0b;--surface-2:#141414;--surface-3:#1c1c1c;--border:#242424;--border-soft:#1a1a1a;--text:#f5f5f5;--muted:#7d7d7d;--muted-2:#5a5a5a;--red:#ff3b30;--red-soft:rgba(255,59,48,.12);--red-line:rgba(255,59,48,.4);--header-bg:rgba(0,0,0,.85);--post-bg:linear-gradient(160deg,#0d0a0a,#080606);--avatar-bg:linear-gradient(140deg,#454545,#0d0d0d);--avatar-border:#2e2e2e;--player-bg:rgba(8,8,8,.96);--toast-bg:#181818;--toast-border:#2e2e2e;--player-bar-bg:#242424;--market-preview-bg:#000;--coin-pack-bg:linear-gradient(160deg,#141414,#0a0a0a)}
body.light{--bg:#f2f3f5;--surface:#fff;--surface-2:#f0f1f3;--surface-3:#e6e8eb;--border:#d5d8dc;--border-soft:#e8eaed;--text:#111418;--muted:#5b6470;--muted-2:#8a929c;--header-bg:rgba(255,255,255,.92);--post-bg:linear-gradient(160deg,#fff,#f8f9fb);--avatar-bg:linear-gradient(140deg,#dfe3e8,#b9c0c8);--avatar-border:#cfd4da;--player-bg:rgba(255,255,255,.97);--toast-bg:#fff;--toast-border:#d5d8dc;--player-bar-bg:#d5d8dc;--market-preview-bg:#f2f3f5;--coin-pack-bg:linear-gradient(160deg,#fff,#eef0f2)}
body{background:var(--bg);color:var(--text);font-family:-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,Helvetica,Arial,sans-serif;font-size:14px;line-height:1.45;padding-top:56px}
button{font-family:inherit;font-size:inherit;cursor:pointer;border:none;background:none;color:inherit}
input,textarea{font-family:inherit}
::-webkit-scrollbar{width:8px;height:8px}
::-webkit-scrollbar-track{background:var(--bg)}
::-webkit-scrollbar-thumb{background:var(--border);border-radius:10px}
svg{display:block}
header{position:fixed;top:0;left:0;right:0;height:56px;z-index:100;background:var(--header-bg);backdrop-filter:blur(14px);border-bottom:1px solid var(--border);box-shadow:0 4px 20px rgba(0,0,0,.4)}
.header-inner{max-width:1440px;margin:0 auto;height:100%;display:flex;align-items:center;gap:14px;padding:0 20px}
.logo{display:flex;align-items:center;gap:10px;cursor:pointer}
.logo-mark{width:36px;height:36px;border-radius:11px;background:var(--text);color:var(--bg);display:flex;align-items:center;justify-content:center;font-weight:800;font-size:16px}
.logo-text{font-weight:700;font-size:15px}
.logo-text span{color:var(--red)}
.search{flex:1;max-width:440px;position:relative}
.search input{width:100%;height:38px;border-radius:11px;background:var(--surface-2);border:1px solid var(--border);color:var(--text);padding:0 14px 0 40px;font-size:13.5px;outline:none}
.search svg{position:absolute;left:14px;top:50%;transform:translateY(-50%);color:var(--muted)}
.header-nav{margin-left:auto;display:flex;align-items:center;gap:6px}
.icon-btn{width:38px;height:38px;border-radius:10px;display:flex;align-items:center;justify-content:center;color:var(--muted)}
.icon-btn:hover{background:var(--surface-2);color:var(--red)}
.header-av{margin-left:4px;cursor:pointer;display:flex;align-items:center;gap:4px;flex-wrap:wrap;max-width:340px}
.avatar{border-radius:50%;flex-shrink:0;background:var(--avatar-bg);display:flex;align-items:center;justify-content:center;font-weight:700;color:var(--text);border:1px solid var(--avatar-border);overflow:hidden}
.avatar img{width:100%;height:100%;object-fit:cover;border-radius:50%;display:block}
.avatar.a28{width:28px;height:28px;font-size:10.5px}.avatar.a36{width:36px;height:36px;font-size:12.5px}.avatar.a40{width:40px;height:40px;font-size:13px}.avatar.a44{width:44px;height:44px;font-size:14px}.avatar.a58{width:58px;height:58px;font-size:18px}.avatar.a80{width:82px;height:82px;font-size:26px;border-width:2px}
.avatar-wrap{position:relative;display:inline-flex;border-radius:50%}
.avatar-wrap > .avatar{position:relative;z-index:1}
.admin-badge{display:inline-flex;align-items:center;padding:2px 8px;border-radius:6px;background:var(--red-soft);border:1px solid var(--red-line);color:var(--red);font-size:11px;font-weight:800;text-transform:uppercase;margin-left:6px;vertical-align:middle}
.vip-badge{display:inline-flex;align-items:center;padding:2px 9px;border-radius:6px;background:linear-gradient(135deg,#ffd700,#ff9500);color:#000;font-size:11px;font-weight:900;text-transform:uppercase;margin-left:6px;vertical-align:middle;white-space:nowrap}
.gender-badge{display:inline-flex;align-items:center;padding:2px 9px;border-radius:6px;font-size:11px;font-weight:900;text-transform:uppercase;margin-left:6px;vertical-align:middle;white-space:nowrap}
.gender-girl{background:linear-gradient(135deg,#ff69b4,#ff1493);color:#fff}
.gender-boy{background:linear-gradient(135deg,#1e3a8a,#0c1e5e);color:#fff}
.gender-child{background:linear-gradient(135deg,#fff,#f0f0f0);color:#000}
.gender-unknown{background:linear-gradient(135deg,#666,#444);color:#ddd}
.role-badge{display:inline-flex;align-items:center;gap:4px;padding:2px 9px;border-radius:6px;font-size:11px;font-weight:900;text-transform:uppercase;margin-left:6px;vertical-align:middle;white-space:nowrap}
.cover{height:180px;position:relative;overflow:hidden;background:var(--surface-2)}
.cover.style-none{background:linear-gradient(135deg,#2a2a2a,#0a0a0a)}
.cover.style-galaxy{background:radial-gradient(ellipse at 30% 40%,#3a0f0d 0%,#000 40%,#1a0a2e 70%,#000 100%)}
.cover.style-fire{background:radial-gradient(circle at 50% 100%,#ffe55c 0%,#ffcc00 10%,#ff3b30 30%,#8a0f0a 60%,#000 100%)}
.layout{max-width:1440px;margin:0 auto;padding:20px;display:grid;grid-template-columns:250px minmax(0,1fr) 320px;gap:20px;align-items:start;position:relative;z-index:1}
.card{background:var(--surface);border:1px solid var(--border);border-radius:18px}
.left{position:sticky;top:76px}
.menu{padding:8px}
.menu-item{display:flex;align-items:center;gap:12px;padding:10px 14px;border-radius:11px;color:var(--muted);text-decoration:none;font-size:14.5px;font-weight:500;position:relative;cursor:pointer;transition:background .15s,color .15s}
.menu-item:hover{background:var(--surface-2);color:var(--text)}
.menu-item.active{background:var(--surface-3);color:var(--text)}
.menu-item.active::before{content:'';position:absolute;left:0;top:50%;transform:translateY(-50%);width:3px;height:20px;border-radius:0 3px 3px 0;background:var(--red)}
.menu-item .badge{margin-left:auto;background:var(--red);color:#fff;font-size:11px;font-weight:700;padding:1px 7px;border-radius:20px}
.menu-sep{height:1px;background:var(--border-soft);margin:10px 14px}
.left-footer{padding:16px 18px;font-size:11.5px;color:var(--muted-2);line-height:1.6}
.feed{display:flex;flex-direction:column;gap:16px;min-width:0}
.right{position:sticky;top:76px;display:flex;flex-direction:column;gap:16px}
.btn-primary{background:linear-gradient(135deg,#ff3b30,#d42a22);color:#fff;font-weight:600;font-size:14px;padding:10px 22px;border-radius:10px;cursor:pointer}
.btn-primary:disabled{opacity:.3;cursor:not-allowed}
.btn-ghost{background:var(--surface-2);border:1px solid var(--border);color:var(--text);padding:9px 18px;border-radius:10px;font-size:13.5px;font-weight:500;cursor:pointer}
.row-btn{background:var(--surface-2);border:1px solid var(--border);color:var(--text);font-size:13px;padding:7px 15px;border-radius:9px;cursor:pointer}
.row-btn:hover{background:var(--red);color:#fff;border-color:var(--red)}
.page{padding:22px}
.page-head{display:flex;align-items:flex-start;justify-content:space-between;gap:14px;margin-bottom:18px;flex-wrap:wrap}
.page-title{font-size:20px;font-weight:700;position:relative;display:inline-block;padding-bottom:8px}
.page-title::after{content:'';position:absolute;left:0;bottom:0;height:2px;width:44px;background:var(--red);border-radius:2px}
.page-sub{font-size:13px;color:var(--muted-2);margin-top:4px}
.page-actions{display:flex;gap:8px;flex-wrap:wrap;align-items:center}
.track-list{display:flex;flex-direction:column;gap:2px}
.track{display:flex;align-items:center;gap:12px;padding:10px 12px;border-radius:11px;cursor:pointer;position:relative;transition:background .15s}
.track:hover{background:var(--surface-2)}
.track.active{background:linear-gradient(90deg,var(--red-soft),var(--surface-3) 60%)}
.track-play{width:38px;height:38px;border-radius:50%;background:var(--surface-3);border:1px solid var(--border);display:flex;align-items:center;justify-content:center;flex-shrink:0;font-size:14px;cursor:pointer}
.track.active .track-play{background:var(--red);color:#fff;border-color:var(--red)}
.track-info{min-width:0;flex:1}
.track-title{font-size:14.5px;font-weight:500;white-space:nowrap;overflow:hidden;text-overflow:ellipsis}
.track-artist{font-size:12px;color:var(--muted-2);margin-top:1px}
.track-dur{font-size:12.5px;color:var(--muted-2);flex-shrink:0}
.player{position:fixed;left:0;right:0;bottom:0;z-index:90;background:var(--player-bg);backdrop-filter:blur(14px);border-top:1px solid var(--red-line);transform:translateY(110%);transition:transform .3s}
.player.show{transform:translateY(0)}
.player-inner{max-width:1440px;margin:0 auto;padding:12px 20px}
.player-row{display:flex;align-items:center;gap:14px}
.player-track{display:flex;align-items:center;gap:12px;min-width:0;width:240px;flex-shrink:0}
.player-title{font-size:13.5px;font-weight:600;white-space:nowrap;overflow:hidden;text-overflow:ellipsis}
.player-artist{font-size:12px;color:var(--muted-2)}
.player-btn{width:42px;height:42px;border-radius:50%;background:var(--text);color:var(--bg);display:flex;align-items:center;justify-content:center;flex-shrink:0;font-size:15px;cursor:pointer}
.player-skip{width:36px;height:36px;border-radius:50%;background:transparent;border:1px solid var(--border);color:var(--muted);display:flex;align-items:center;justify-content:center;flex-shrink:0;font-size:13px;cursor:pointer}
.player-bar{flex:1;height:6px;border-radius:6px;background:var(--player-bar-bg);overflow:hidden;cursor:pointer}
.player-fill{height:100%;width:0%;background:linear-gradient(90deg,var(--red),#ff7a72);border-radius:6px}
.player-time{font-size:12px;color:var(--muted-2);flex-shrink:0;min-width:88px;text-align:right}
.post{padding:16px 16px 6px;background:var(--post-bg);border:1px solid var(--border);border-radius:18px}
.post-head{display:flex;align-items:center;gap:12px;margin-bottom:12px}
.post-author{font-weight:600;font-size:14.5px;display:flex;align-items:center;gap:6px;flex-wrap:wrap}
.post-time{font-size:12px;color:var(--muted-2);margin-top:1px}
.post-text{font-size:15px;line-height:1.55;margin-bottom:14px;white-space:pre-wrap;word-break:break-word}
.post-sticker{font-size:100px;line-height:1;text-align:center;margin:10px 0 14px;padding:22px;background:var(--surface-2);border-radius:16px;border:2px solid var(--red-line)}
.post-actions{display:flex;border-top:1px solid var(--border-soft);margin:0 -16px;padding:0 8px}
.action{flex:1;display:flex;align-items:center;justify-content:center;gap:8px;padding:11px;border-radius:10px;color:var(--muted);font-size:13.5px;font-weight:500;margin:5px 2px;cursor:pointer}
.action:hover{background:var(--red-soft);color:var(--red)}
.action.liked{color:var(--red)}
.post-media-box{margin-bottom:14px}
.post-media-box audio,.post-media-box video{width:100%;border-radius:12px;display:block;background:#000;max-height:400px}
.post-media-name{font-size:12px;color:var(--muted-2);margin-top:6px;padding:0 4px}
.composer{padding:16px}
.composer-top{display:flex;gap:14px;align-items:flex-start}
.composer textarea{flex:1;background:var(--surface-2);border:1px solid var(--border);border-radius:14px;color:var(--text);padding:12px 16px;font-size:14.5px;resize:none;min-height:46px;max-height:220px;outline:none}
.composer-actions{display:flex;align-items:center;gap:4px;margin-top:14px;padding-top:14px;border-top:1px solid var(--border-soft);flex-wrap:wrap}
.chip{display:flex;align-items:center;gap:7px;padding:8px 13px;border-radius:10px;font-size:13.5px;color:var(--muted);cursor:pointer;position:relative}
.chip:hover{background:var(--surface-2);color:var(--red)}
.chip input{display:none}
.composer-sticker-preview,.composer-media-preview{display:flex;align-items:center;gap:12px;margin-top:12px;padding:12px;border-radius:12px;background:var(--surface-2);border:2px solid var(--red-line)}
.composer-sticker-preview .big-sticker{font-size:48px;line-height:1}
.composer-sticker-preview .close-sticker,.composer-media-preview .close-sticker{width:30px;height:30px;border-radius:50%;background:var(--surface-3);color:var(--muted);display:flex;align-items:center;justify-content:center;font-size:14px;cursor:pointer}
.voices-card{display:flex;align-items:center;gap:12px;padding:14px 16px}
.voices-icon{width:44px;height:44px;border-radius:13px;background:linear-gradient(135deg,#fff,#e0e0e0);color:#000;display:flex;align-items:center;justify-content:center;font-size:22px;flex-shrink:0}
.voices-info{flex:1;min-width:0}
.voices-label{font-size:11.5px;color:var(--muted-2);text-transform:uppercase;letter-spacing:.5px;font-weight:700}
.voices-amount{font-size:22px;font-weight:800;line-height:1.1}
.profile-hero{padding:0;overflow:hidden}
.profile-hero .cover{height:220px}
.hero-body{padding:0 24px 24px;margin-top:-48px;position:relative}
.hero-top{display:flex;align-items:flex-end;justify-content:space-between;gap:14px;flex-wrap:wrap}
.hero-top .avatar-wrap{padding:5px;background:var(--surface);border-radius:50%}
.hero-name{font-size:24px;font-weight:700;margin-top:14px;display:inline-flex;align-items:center;flex-wrap:wrap}
.hero-status{color:var(--muted);font-size:14px;margin-top:4px}
.hero-meta{color:var(--muted-2);font-size:13px;margin-top:9px}
.hero-stats{display:flex;gap:24px;margin-top:18px;padding-top:16px;border-top:1px solid var(--border-soft)}
.pstat b{display:block;font-size:14.5px;font-weight:700}
.pstat span{font-size:12px;color:var(--muted-2)}
.about-card{padding:18px}
.fav-label{font-size:11px;text-transform:uppercase;letter-spacing:1px;color:var(--muted-2);font-weight:700;margin-bottom:14px}
.about-text{font-size:14px;line-height:1.65;white-space:pre-wrap;opacity:.85}
.phone-line{display:inline-flex;align-items:center;gap:6px;padding:4px 12px;border-radius:20px;background:var(--surface-2);border:1px solid var(--border);font-size:12.5px;color:var(--muted);font-weight:500;margin-top:6px}
.phone-line b{color:var(--text);font-weight:700}
.simple-row{display:flex;align-items:center;gap:13px;padding:12px 8px;border-radius:11px;cursor:pointer;transition:background .15s}
.simple-row:hover{background:var(--surface-2)}
.simple-row .grow{flex:1;min-width:0}
.simple-name{font-size:14.5px;font-weight:500}
.simple-sub{font-size:12.5px;color:var(--muted-2);margin-top:2px}
.empty{padding:56px 20px;text-align:center;color:var(--muted-2);font-size:14.5px}
.setting-row{display:flex;align-items:center;gap:16px;padding:14px 6px;border-bottom:1px solid var(--border-soft)}
.setting-row:last-child{border-bottom:none}
.setting-row .grow{flex:1}
.setting-name{font-size:14px;font-weight:500}
.theme-btn{display:flex;align-items:center;gap:6px;padding:9px 16px;border-radius:10px;border:1px solid var(--border);background:var(--surface-2);color:var(--text);font-size:13px;font-weight:600;cursor:pointer}
.theme-btn.active{background:var(--red);color:#fff;border-color:var(--red)}
.market-group{margin-bottom:26px}
.market-group-title{font-size:12px;font-weight:700;text-transform:uppercase;letter-spacing:1px;color:var(--muted-2);margin-bottom:12px;padding-bottom:8px;border-bottom:1px solid var(--border-soft)}
.market-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(200px,1fr));gap:14px}
.market-item{background:var(--surface-2);border:1px solid var(--border);border-radius:16px;padding:16px;display:flex;flex-direction:column;gap:12px}
.market-item.vip-item{background:linear-gradient(160deg,rgba(255,215,0,.12),rgba(255,149,0,.04));border-color:rgba(255,215,0,.4)}
.market-preview{height:74px;display:flex;align-items:center;justify-content:center;background:var(--market-preview-bg);border-radius:11px;overflow:hidden}
.market-name{font-size:14px;font-weight:600;line-height:1.3}
.market-desc{font-size:12px;color:var(--muted-2);line-height:1.4;flex:1}
.market-buy{display:flex;align-items:center;justify-content:center;gap:6px;padding:10px;border-radius:10px;background:linear-gradient(135deg,#ff3b30,#d42a22);color:#fff;font-weight:700;font-size:13.5px;cursor:pointer}
.market-buy.vip-buy{background:linear-gradient(135deg,#ffd700,#ff9500);color:#000}
.market-buy.vip-buy:disabled{opacity:.5;cursor:not-allowed}
.market-owned{display:flex;align-items:center;justify-content:center;padding:10px;border-radius:10px;background:rgba(74,222,128,.14);color:#22a355;font-weight:600;font-size:13.5px}
.vip-btn-row{display:grid;grid-template-columns:1fr 1fr;gap:8px}
.sticker-pack{background:var(--surface-2);border:1px solid var(--border);border-radius:18px;padding:16px;display:flex;flex-direction:column;gap:14px}
.sticker-pack.owned{border-color:rgba(74,222,128,.4);background:rgba(74,222,128,.04)}
.sticker-pack-head{display:flex;align-items:center;gap:12px}
.sticker-pack-cover{width:56px;height:56px;border-radius:14px;background:#fff;display:flex;align-items:center;justify-content:center;font-size:28px;flex-shrink:0;border:2px solid #ff3b30}
.sticker-pack-cover.theme-black{border-color:#111}
.sticker-pack-name{font-size:14.5px;font-weight:700}
.sticker-pack-count{font-size:12px;color:var(--muted-2);margin-top:2px}
.sticker-pack-stickers{display:flex;flex-wrap:wrap;gap:7px}
.sticker-tile{width:60px;height:60px;border-radius:13px;background:#fff;display:flex;align-items:center;justify-content:center;font-size:30px;cursor:pointer;border:2px solid #ff3b30;flex-shrink:0;user-select:none;transition:transform .15s}
.sticker-tile.theme-black{border-color:#111}
.sticker-tile:hover{transform:scale(1.1)}
.stickers-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(250px,1fr));gap:16px}
.stickers-mine-grid{display:flex;flex-wrap:wrap;gap:9px;padding:16px;background:var(--surface-2);border-radius:15px;border:1px solid var(--border);min-height:80px}
.sticker-buy-row{display:flex;align-items:center;gap:8px;justify-content:space-between;margin-top:4px}
.sticker-buy-btn{flex:1;display:flex;align-items:center;justify-content:center;gap:6px;padding:10px;border-radius:10px;background:linear-gradient(135deg,#ff3b30,#d42a22);color:#fff;font-weight:700;font-size:13.5px;cursor:pointer}
.sticker-buy-btn.disabled{opacity:.5;cursor:not-allowed}
.voice-badge{display:inline-flex;align-items:center;gap:4px;font-weight:800;font-size:13.5px}
.voice-icon-mini{display:inline-flex;align-items:center;justify-content:center;width:22px;height:22px;border-radius:7px;background:#fff;color:#000;font-size:12px}
.coin{display:inline-flex;align-items:center;justify-content:center;width:26px;height:26px;border-radius:50%;background:radial-gradient(circle at 30% 30%,#fff 0%,#e8e8e8 45%,#b8b8b8 100%);border:1.5px solid #8a8a8a;color:#000;font-weight:900;font-size:8px;flex-shrink:0;line-height:1}
.coin.lg{width:42px;height:42px;font-size:13px;border-width:2px}
.coin-balance{display:flex;align-items:center;gap:8px;padding:5px 12px 5px 5px;background:var(--surface-2);border:1px solid var(--border);border-radius:24px;font-size:13.5px;font-weight:700;flex-shrink:0}
.coin-packs{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:16px;margin-bottom:26px}
.coin-pack{background:var(--coin-pack-bg);border:1px solid var(--border);border-radius:18px;padding:24px 20px;text-align:center}
.coin-pack.featured{border-color:var(--red);box-shadow:0 0 30px var(--red-soft)}
.coin-pack-amount{font-size:28px;font-weight:900;line-height:1;margin-bottom:5px}
.coin-pack-amount span{font-size:15px;color:var(--muted);font-weight:700;margin-left:4px}
.coin-pack-label{font-size:12px;color:var(--muted-2);margin-bottom:18px}
.coin-pack-price{font-size:24px;font-weight:800;margin-bottom:16px}
.coin-pack-price small{font-size:14px;color:var(--muted);font-weight:600}
.coin-pack-buy{display:block;width:100%;padding:12px;border-radius:11px;background:linear-gradient(135deg,#ff3b30,#d42a22);color:#fff;font-weight:700;font-size:14px;cursor:pointer}
.game-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(175px,1fr));gap:14px}
.game-card{background:var(--surface-2);border:1px solid var(--border);border-radius:16px;padding:20px 16px;cursor:pointer;text-align:center;transition:border-color .15s}
.game-card:hover{border-color:var(--red-line)}
.game-icon{font-size:42px;margin-bottom:11px}
.game-name{font-size:14.5px;font-weight:700;margin-bottom:3px}
.game-desc{font-size:12px;color:var(--muted-2)}
.game-container{padding:20px;min-height:560px;display:flex;flex-direction:column;align-items:center;gap:16px}
.game-topbar{display:flex;align-items:center;justify-content:space-between;width:100%;max-width:600px;gap:14px;flex-wrap:wrap}
.game-score{font-size:14.5px;font-weight:600}
.game-score b{color:var(--red);font-size:17px}
.game-restart{background:var(--surface-2);border:1px solid var(--border);color:var(--text);font-size:13px;padding:8px 18px;border-radius:9px;cursor:pointer}
.game-status{font-size:14.5px;color:var(--muted);text-align:center;min-height:24px}
.toast-container{position:fixed;top:76px;right:22px;z-index:500;display:flex;flex-direction:column;gap:9px;pointer-events:none}
.toast{background:var(--toast-bg);border:1px solid var(--toast-border);border-left:3px solid var(--red);padding:12px 18px;border-radius:11px;font-size:13.5px;color:var(--text);box-shadow:0 14px 44px rgba(0,0,0,.45);pointer-events:auto;max-width:360px}
@keyframes toastOut{to{opacity:0;transform:translateX(44px)}}
.modal-backdrop{position:fixed;inset:0;z-index:200;background:rgba(0,0,0,.7);display:flex;align-items:center;justify-content:center;padding:22px;overflow-y:auto}
.modal-backdrop[hidden]{display:none}
.modal{background:var(--surface);border:1px solid var(--border);border-radius:20px;width:100%;max-width:580px;max-height:calc(100vh - 44px);display:flex;flex-direction:column;box-shadow:0 28px 90px var(--red-soft);animation:modalPop .3s cubic-bezier(.34,1.56,.64,1) backwards}
@keyframes modalPop{0%{transform:scale(.9) translateY(20px)}100%{transform:scale(1) translateY(0)}}
.modal-head{display:flex;align-items:center;justify-content:space-between;padding:20px 22px 14px;border-bottom:1px solid var(--border-soft)}
.modal-head h2{font-size:17px;font-weight:700}
.modal-body{padding:20px 22px;overflow-y:auto;display:flex;flex-direction:column;gap:18px}
.modal-foot{display:flex;gap:10px;justify-content:flex-end;padding:16px 22px;border-top:1px solid var(--border-soft)}
.field{display:flex;flex-direction:column;gap:8px}
.field > span{font-size:12px;color:var(--muted);font-weight:500}
.field input,.field textarea{background:var(--surface-2);border:1px solid var(--border);border-radius:11px;color:var(--text);padding:11px 14px;font-size:14px;outline:none;resize:vertical}
#devPassModal{z-index:10050}
#paymentModal{z-index:10050}
.dev-toggle-btn{position:fixed;bottom:22px;left:22px;width:44px;height:44px;border-radius:13px;background:var(--red-soft);border:1px solid var(--red-line);color:var(--red);font-size:20px;display:flex;align-items:center;justify-content:center;z-index:10001;cursor:pointer;opacity:.15}
.dev-toggle-btn:hover{opacity:1}
.dev-panel-backdrop{position:fixed;inset:0;z-index:10000;background:rgba(0,0,0,.88);display:flex;align-items:center;justify-content:center;padding:22px;overflow-y:auto}
.dev-panel-backdrop[hidden]{display:none}
.dev-panel{background:var(--surface);border:1px solid var(--red-line);border-radius:22px;width:100%;max-width:660px;max-height:calc(100vh - 44px);display:flex;flex-direction:column}
.dev-head{display:flex;align-items:center;justify-content:space-between;padding:18px 22px;border-bottom:1px solid var(--border-soft);background:linear-gradient(90deg,var(--red-soft),transparent)}
.dev-head h2{font-size:17px;font-weight:800;display:flex;align-items:center;gap:10px}
.dev-head .dev-tag{font-size:10px;padding:2px 9px;border-radius:20px;background:var(--red);color:#fff;font-weight:800;letter-spacing:1px}
.dev-body{padding:18px 22px;overflow-y:auto;display:flex;flex-direction:column;gap:20px}
.dev-section{border:1px solid var(--border);border-radius:13px;padding:16px;background:var(--surface-2)}
.dev-section-title{font-size:11px;font-weight:800;letter-spacing:1px;text-transform:uppercase;color:var(--red);margin-bottom:12px}
.dev-row{display:flex;flex-wrap:wrap;gap:9px;margin-bottom:9px;align-items:center}
.dev-row:last-child{margin-bottom:0}
.dev-btn-sm{padding:8px 15px;border-radius:9px;border:1px solid var(--border);background:var(--surface-3);color:var(--text);font-size:13px;font-weight:600;cursor:pointer}
.dev-btn-sm.primary{background:linear-gradient(135deg,#ff3b30,#d42a22);border-color:var(--red);color:#fff}
.dev-btn-sm.danger{background:transparent;border-color:var(--red-line);color:var(--red)}
.dev-btn-sm.success{background:rgba(74,222,128,.1);border-color:rgba(74,222,128,.4);color:#22a355}
.dev-btn-sm.vip{background:linear-gradient(135deg,#ffd700,#ff9500);border-color:#ffd700;color:#000;font-weight:800}
.dev-input{padding:8px 13px;border-radius:9px;border:1px solid var(--border);background:var(--surface-3);color:var(--text);font-size:13px;outline:none;flex:1;min-width:110px}
.dev-label{font-size:12.5px;color:var(--muted)}
.dev-val{font-size:13.5px;font-weight:800;color:var(--text)}
.dev-banned-overlay{position:fixed;inset:0;z-index:9998;background:linear-gradient(160deg,#1a0000,#000 40%,#2a0808);display:flex;align-items:center;justify-content:center;flex-direction:column;gap:18px;text-align:center;padding:32px;color:#fff}
.dev-banned-overlay[hidden]{display:none}
.dev-banned-icon{font-size:90px}
.dev-banned-title{font-size:30px;font-weight:900;color:var(--red)}
.code-hero{background:rgba(28,28,30,.7);border:1px solid rgba(255,255,255,.12);border-radius:30px;padding:40px 28px;text-align:center;margin-bottom:24px}
.code-hero-icon{font-size:70px;margin-bottom:16px;display:inline-block}
.code-hero-title{font-size:24px;font-weight:800;margin-bottom:7px}
.code-hero-sub{font-size:14px;color:var(--muted);margin-bottom:24px}
.code-input-row{display:flex;gap:11px;max-width:520px;margin:0 auto}
.code-input{flex:1;height:58px;padding:0 20px;border-radius:17px;border:2px solid rgba(255,255,255,.14);background:rgba(20,20,22,.7);color:var(--text);font-size:18px;font-weight:700;letter-spacing:3px;text-transform:uppercase;outline:none;font-family:monospace}
.code-activate-btn{padding:0 32px;height:58px;border-radius:17px;background:linear-gradient(180deg,#ff3b30,#d42a22);color:#fff;font-size:15px;font-weight:800;cursor:pointer;white-space:nowrap}
.code-result{margin-top:20px;min-height:26px;font-size:15px;font-weight:700;text-align:center}
.code-result.ok{color:#22a355}
.code-result.err{color:var(--red)}
.code-history{display:flex;flex-direction:column;background:var(--surface-2);border-radius:13px;padding:4px 16px;border:1px solid var(--border)}
.code-history-item{display:flex;align-items:center;gap:12px;padding:12px 0;border-bottom:1px solid var(--border-soft)}
.code-history-check{color:#22a355;font-weight:800;font-size:15px}
.code-history-name{font-family:monospace;font-size:13.5px;font-weight:700;min-width:150px;letter-spacing:1px}
.code-history-desc{font-size:12.5px;color:var(--muted);flex:1}
.gallery-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(170px,1fr));gap:12px;margin-top:16px}
.gallery-item{position:relative;aspect-ratio:1;border-radius:13px;overflow:hidden;border:1px solid var(--border);background:var(--surface-2);cursor:pointer}
.gallery-item img{width:100%;height:100%;object-fit:cover;display:block}
.gallery-item .del{position:absolute;top:7px;right:7px;width:28px;height:28px;border-radius:50%;background:rgba(0,0,0,.7);color:#fff;display:flex;align-items:center;justify-content:center;font-size:14px;cursor:pointer}
.gallery-upload{border:2px dashed var(--border);border-radius:13px;aspect-ratio:1;display:flex;flex-direction:column;align-items:center;justify-content:center;gap:10px;cursor:pointer;color:var(--muted);padding:14px}
.gallery-upload input{display:none}
.gallery-upload .big{font-size:40px;line-height:1}
.gallery-viewer{position:fixed;inset:0;z-index:400;background:rgba(0,0,0,.96);display:flex;align-items:center;justify-content:center;padding:40px 20px;cursor:pointer}
.gallery-viewer[hidden]{display:none}
.gallery-viewer img{max-width:100%;max-height:100%;border-radius:14px}
.gv-close{position:absolute;top:22px;right:26px;width:48px;height:48px;border-radius:50%;background:rgba(255,255,255,.1);color:#fff;display:flex;align-items:center;justify-content:center;font-size:22px;cursor:pointer}
.quality-badge{display:inline-flex;align-items:center;justify-content:center;padding:2px 7px;border-radius:5px;font-size:9.5px;font-weight:900;background:linear-gradient(135deg,#ffd700,#ff9500);color:#000;white-space:nowrap;flex-shrink:0;line-height:1.2}
.live-badge{display:inline-flex;align-items:center;gap:3px;padding:2px 7px;border-radius:5px;font-size:9.5px;font-weight:900;background:linear-gradient(135deg,#ff3b30,#c43028);color:#fff;flex-shrink:0}
.reg-tabs{display:grid;grid-template-columns:1fr 1fr;gap:8px;margin-bottom:18px}
.reg-tab{padding:12px;border-radius:12px;background:var(--surface-2);border:2px solid var(--border);color:var(--muted);font-weight:600;font-size:14px;cursor:pointer;display:flex;align-items:center;justify-content:center;gap:7px}
.reg-tab.active{background:var(--red-soft);border-color:var(--red);color:var(--red)}
.reg-step{display:flex;flex-direction:column;gap:14px}
.reg-code-hint{font-size:12px;color:var(--muted-2);text-align:center;padding:10px;background:var(--surface-2);border-radius:8px;border:1px dashed var(--border)}
.reg-code-hint b{color:var(--red);font-family:monospace;letter-spacing:2px;font-size:14px}
.pay-modal{max-width:520px}
.pay-amount-box{text-align:center;padding:20px;background:linear-gradient(135deg,rgba(255,215,0,.15),rgba(255,149,0,.05));border:1px solid rgba(255,215,0,.4);border-radius:18px;margin-bottom:20px}
.pay-amount-label{font-size:12px;color:var(--muted-2);text-transform:uppercase;letter-spacing:1px;font-weight:700;margin-bottom:6px}
.pay-amount-value{font-size:32px;font-weight:900;color:#ffd700;line-height:1}
.pay-amount-desc{font-size:12.5px;color:var(--muted);margin-top:8px}
.pay-methods{display:flex;flex-direction:column;gap:10px}
.pay-method{display:flex;align-items:center;gap:14px;padding:14px 16px;border-radius:14px;border:2px solid var(--border);background:var(--surface-2);cursor:pointer;transition:border-color .15s}
.pay-method:hover{border-color:var(--red-line)}
.pay-method-logo{width:52px;height:52px;border-radius:12px;display:flex;align-items:center;justify-content:center;font-size:14px;font-weight:900;color:#fff;flex-shrink:0}
.pay-method-logo.tbank{background:linear-gradient(135deg,#ffdd2d,#ffcc00);color:#000}
.pay-method-logo.sber{background:linear-gradient(135deg,#21a038,#0a7a26)}
.pay-method-logo.sbp{background:linear-gradient(135deg,#5b57ff,#8b3fff)}
.pay-method-logo.card{background:linear-gradient(135deg,#444,#222)}
.pay-method-info{flex:1;min-width:0}
.pay-method-name{font-size:14.5px;font-weight:700}
.pay-method-sub{font-size:12px;color:var(--muted-2);margin-top:2px}
.pay-method-arrow{font-size:20px;color:var(--muted);flex-shrink:0}
.pay-summary{padding:14px 16px;background:var(--surface-2);border-radius:12px;border:1px solid var(--border);margin-bottom:16px;font-size:13.5px}
.pay-summary-row{display:flex;justify-content:space-between;padding:4px 0}
.pay-summary-row.total{font-size:16px;font-weight:800;border-top:1px solid var(--border-soft);margin-top:6px;padding-top:10px}
.pay-processing{text-align:center;padding:40px 20px;display:flex;flex-direction:column;align-items:center;gap:20px}
.pay-spinner{width:60px;height:60px;border-radius:50%;border:4px solid var(--border);border-top-color:var(--red);animation:paySpin 1s linear infinite}
@keyframes paySpin{to{transform:rotate(360deg)}}
.pay-success{text-align:center;padding:30px 20px;display:flex;flex-direction:column;align-items:center;gap:14px}
.pay-success-icon{font-size:70px}
.pay-success-title{font-size:22px;font-weight:900;color:#22a355}
.pay-success-sub{font-size:14px;color:var(--muted)}
.pay-demo-warning{font-size:11.5px;color:var(--muted-2);text-align:center;padding:10px;background:var(--surface-2);border-radius:8px;border:1px dashed var(--border);line-height:1.5}
.pay-demo-warning b{color:var(--red)}
.pay-back-btn{display:inline-flex;align-items:center;gap:7px;padding:8px 16px;border-radius:10px;background:var(--surface-2);border:1px solid var(--border);color:var(--text);font-size:13.5px;font-weight:600;cursor:pointer;flex-shrink:0}
.pay-back-btn:hover{background:var(--surface-3);border-color:var(--red-line);color:var(--red)}
.notif-modal{max-width:430px;padding:28px 24px;text-align:center}
.notif-hero{display:flex;align-items:center;justify-content:center;gap:12px;margin-bottom:20px}
.notif-logo{width:52px;height:52px;border-radius:15px;background:linear-gradient(135deg,#ff3b30,#d42a22);color:#fff;display:flex;align-items:center;justify-content:center;font-weight:900;font-size:22px;box-shadow:0 8px 24px rgba(255,59,48,.45)}
.notif-app{font-size:19px;font-weight:800}
.notif-title{font-size:19px;font-weight:800;margin-bottom:10px}
.notif-desc{font-size:13.5px;color:var(--muted);line-height:1.6;margin-bottom:22px}
.notif-actions{display:grid;grid-template-columns:1fr 1fr;gap:10px;margin-bottom:14px}
.notif-btn{padding:13px;border-radius:12px;font-size:14px;font-weight:700;cursor:pointer;border:none}
.notif-btn-deny{background:var(--surface-2);border:1px solid var(--border);color:var(--text)}
.notif-btn-allow{background:linear-gradient(135deg,#ff3b30,#d42a22);color:#fff;box-shadow:0 6px 18px rgba(255,59,48,.4)}
.notif-hint{font-size:11.5px;color:var(--muted-2);line-height:1.5}
.notif-hint b{color:var(--text)}
#main{animation:none !important;opacity:1 !important;visibility:visible !important;display:flex !important;flex-direction:column !important;gap:16px !important}
#main > *, #main .card, #main .page, #main .profile-hero, #main .post, #main article, #main .composer, #main .empty{animation:none !important;opacity:1 !important;visibility:visible !important;transform:none !important}
#main.fadeIn{animation:viewFadeIn .25s ease-out !important}
@keyframes viewFadeIn{0%{opacity:.55;transform:translateY(3px)}100%{opacity:1;transform:translateY(0)}}
.hero-name{background:linear-gradient(120deg,var(--text) 0%,var(--text) 35%,var(--red) 50%,var(--text) 65%,var(--text) 100%);background-size:220% 100%;-webkit-background-clip:text;background-clip:text;color:transparent;animation:nameShimmer 6s linear infinite}
@keyframes nameShimmer{0%{background-position:120% 0}100%{background-position:-120% 0}}
@keyframes spin3d{from{transform:rotate(0deg)}to{transform:rotate(360deg)}}
@keyframes ringPulse3d{0%{transform:scale(1);opacity:.95}100%{transform:scale(1.3);opacity:0}}
@keyframes orbit3d{0%{transform:rotate(0deg)}100%{transform:rotate(360deg)}}
@keyframes glowPulse3d{0%,100%{transform:scale(1);opacity:.75}50%{transform:scale(1.18);opacity:1}}
@keyframes ripple3d{0%{transform:scale(1);opacity:1}100%{transform:scale(1.7);opacity:0}}
@keyframes neon3d{0%,100%{opacity:1}50%{opacity:.45}}
@keyframes waveMove{0%{background-position:0% 50%}50%{background-position:100% 50%}100%{background-position:0% 50%}}
.avatar-wrap.style-spin::before{content:'';position:absolute;inset:-6px;border-radius:50%;background:conic-gradient(from 0deg,transparent,var(--red) 80deg,#fff 130deg,transparent 170deg,var(--red) 260deg,#fff 310deg,transparent);animation:spin3d 4s linear infinite;z-index:0}
.avatar-wrap.style-pulse::before{content:'';position:absolute;inset:-6px;border-radius:50%;border:2px solid var(--red);animation:ringPulse3d 2.2s ease-out infinite;z-index:0}
.avatar-wrap.style-wave::before{content:'';position:absolute;inset:-6px;border-radius:50%;background:linear-gradient(120deg,var(--red),#fff,var(--red),#000,var(--red));background-size:300% 300%;animation:waveMove 4.5s ease infinite;z-index:0}
.avatar-wrap.style-orbit::before{content:'';position:absolute;inset:-6px;border-radius:50%;background:radial-gradient(circle at 30% 30%,#fff,var(--red),transparent 70%);animation:orbit3d 5s linear infinite;z-index:0}
.avatar-wrap.style-glow::before{content:'';position:absolute;inset:-8px;border-radius:50%;background:radial-gradient(circle,var(--red),transparent 70%);animation:glowPulse3d 2s ease-in-out infinite;z-index:0}
.avatar-wrap.style-ripple::before{content:'';position:absolute;inset:-6px;border-radius:50%;border:2px solid #fff;animation:ripple3d 1.8s ease-out infinite;z-index:0}
.avatar-wrap.style-ripple::after{content:'';position:absolute;inset:-6px;border-radius:50%;border:2px solid var(--red);animation:ripple3d 1.8s ease-out infinite .9s;z-index:0}
.avatar-wrap.style-neon::before{content:'';position:absolute;inset:-4px;border-radius:50%;border:2px solid #fff;box-shadow:0 0 10px #fff,0 0 22px var(--red),0 0 34px var(--red);animation:neon3d 3s ease-in-out infinite;z-index:0}
.avatar-wrap.style-rainbow::before{content:'';position:absolute;inset:-6px;border-radius:50%;background:conic-gradient(from 0deg,#ff3b30,#ff9500,#ffcc00,#34c759,#007aff,#5856d6,#af52de,#ff3b30);animation:spin3d 5s linear infinite;z-index:0}
.avatar-wrap.style-hearts::before{content:'';position:absolute;inset:-8px;border-radius:50%;background:radial-gradient(circle at 20% 20%,rgba(255,120,180,.9),transparent 60%),radial-gradient(circle at 80% 80%,var(--red),transparent 60%);animation:glowPulse3d 3s ease-in-out infinite;z-index:0}
.avatar-wrap.style-flame::before{content:'';position:absolute;inset:-7px;border-radius:50%;background:conic-gradient(from 0deg,var(--red),rgba(255,150,0,.9),rgba(255,230,0,.7),var(--red));animation:spin3d 2s linear infinite;z-index:0}
.avatar-wrap.style-galaxy-av::before{content:'';position:absolute;inset:-6px;border-radius:50%;background:conic-gradient(from 0deg,#5856d6,#007aff,#5856d6,#af52de,#5856d6);animation:spin3d 6s linear infinite;z-index:0}
.avatar-wrap.style-ice::before{content:'';position:absolute;inset:-8px;border-radius:50%;background:radial-gradient(circle,rgba(100,200,255,.98),rgba(0,150,255,.5),transparent 70%);animation:glowPulse3d 2s ease-in-out infinite;z-index:0}
.avatar-wrap.style-diamond::before{content:'';position:absolute;inset:-6px;border-radius:50%;background:conic-gradient(from 0deg,#fff,#b8e0ff 40deg,#fff 80deg,#e0f5ff 120deg,#fff 160deg,#b8e0ff 200deg,#fff 240deg,#e0f5ff 280deg,#fff 320deg,#fff 360deg);animation:spin3d 4s linear infinite;z-index:0}
.avatar-wrap.style-shadow::before{content:'';position:absolute;inset:-12px;border-radius:50%;background:radial-gradient(circle,rgba(0,0,0,.98),rgba(50,0,0,.6),transparent 70%);animation:glowPulse3d 3s ease-in-out infinite;z-index:0}
.avatar-wrap.style-aurora-av::before{content:'';position:absolute;inset:-8px;border-radius:50%;background:linear-gradient(120deg,#34c759,#007aff,#af52de,#34c759);background-size:300% 300%;animation:waveMove 5s ease infinite;z-index:0}
.avatar-wrap.style-sparkle-av::before{content:'';position:absolute;inset:-8px;border-radius:50%;background:radial-gradient(circle at 30% 30%,#fff 3px,transparent 4px),radial-gradient(circle at 70% 70%,#fff 3px,transparent 4px);animation:spin3d 4s linear infinite;z-index:0}
.avatar-wrap.style-pink-glow::before{content:'';position:absolute;inset:-6px;border-radius:50%;background:radial-gradient(circle,#ff69b4,#da70d6,transparent 70%);animation:glowPulse3d 2s ease-in-out infinite;z-index:0;opacity:.7}
.avatar-wrap.style-rose-frame::before{content:'';position:absolute;inset:-4px;border-radius:50%;background:conic-gradient(from 0deg,#ff69b4,#ffc0cb,#ff1493,#da70d6,#ff69b4);animation:spin3d 5s linear infinite;z-index:0}
.avatar-wrap.style-glitter-heart::before{content:'';position:absolute;inset:-4px;border-radius:50%;background:radial-gradient(circle at 30% 30%,#fff 2px,transparent 3px),radial-gradient(circle at 70% 70%,#ff69b4 2px,transparent 3px),radial-gradient(circle at 50% 20%,#da70d6 2px,transparent 3px);animation:spin3d 4s linear infinite;z-index:0}
.avatar-wrap.style-butterfly-av::before{content:'';position:absolute;inset:-6px;border-radius:50%;background:linear-gradient(120deg,#ff69b4,#da70d6,#ff69b4);background-size:300% 300%;animation:waveMove 4s ease infinite;z-index:0;opacity:.8}
.avatar-wrap.style-doll-av::before{content:'';position:absolute;inset:-4px;border-radius:50%;background:linear-gradient(120deg,#ffb6c1,#ff69b4,#da70d6,#ffb6c1);background-size:300% 300%;animation:waveMove 5s ease infinite;z-index:0}
@keyframes fog4k{0%{background-position:0% 50%}50%{background-position:100% 50%}100%{background-position:0% 50%}}
@keyframes linesMove{0%{background-position:0 0}100%{background-position:226px 226px}}
@keyframes coverPulse4k{0%,100%{background-size:100% 100%,100% 100%}50%{background-size:135% 135%,100% 100%}}
@keyframes rainbowSlide4k{to{background-position:-2000px 0}}
@keyframes starsDrift{to{background-position:130px 260px,150px 300px,120px 240px,170px 340px,0 0}}
@keyframes matrixScroll{to{background-position:0 60px,0 0}}
@keyframes snowDrift{to{background-position:110px 220px,140px 280px,160px 320px,120px 240px,180px 360px,0 0}}
.cover.style-fog{background:radial-gradient(circle at 20% 30%,rgba(74,18,16,.7) 0%,transparent 45%),radial-gradient(circle at 80% 70%,rgba(120,30,28,.6) 0%,transparent 45%),#000;background-size:2000px 2000px,2000px 2000px,100% 100%;animation:fog4k 14s ease infinite}
.cover.style-lines{background:repeating-linear-gradient(45deg,#0d0d0d 0 16px,#2a1210 16px 32px);background-size:226px 226px;animation:linesMove 6s linear infinite}
.cover.style-pulse{background:radial-gradient(circle at 50% 130%,var(--red) 0%,rgba(255,59,48,.4) 20%,#000 70%);animation:coverPulse4k 5s ease-in-out infinite}
.cover.style-nebula{background:radial-gradient(circle at 60% 30%,rgba(255,59,48,.7) 0%,transparent 45%),radial-gradient(circle at 30% 70%,rgba(120,40,255,.6) 0%,transparent 45%),#000;background-size:2000px 2000px,2000px 2000px,100% 100%;animation:fog4k 10s ease infinite}
.cover.style-aurora{background:linear-gradient(120deg,#000 0%,#0a4a2a 20%,#34c759 30%,#007aff 50%,#af52de 70%,#0a2a4a 80%,#000 100%);background-size:2000px 2000px;animation:fog4k 9s ease infinite}
.cover.style-matrix-cover{background:repeating-linear-gradient(180deg,#000 0 10px,#0a4a1e 10px 14px,#0f7a2a 14px 16px,#000 16px 28px);background-size:100% 60px;animation:matrixScroll 4s linear infinite}
.cover.style-rainbow-cover{background:linear-gradient(90deg,#ff3b30,#ff9500,#ffcc00,#34c759,#007aff,#5856d6,#af52de,#ff3b30);background-size:2000px 100%;animation:rainbowSlide4k 8s linear infinite}
.cover.style-snow{background:radial-gradient(circle at 20% 30%,#fff 2px,transparent 3px),radial-gradient(circle at 60% 70%,#fff 2px,transparent 3px),linear-gradient(180deg,#0a1e4a,#000);background-size:110px 110px,140px 140px,100% 100%;animation:snowDrift 18s linear infinite}
.cover.style-unicorn{background:linear-gradient(120deg,#ff69b4,#da70d6,#9370db,#da70d6,#ff69b4);background-size:2000px 2000px;animation:fog4k 10s ease infinite}
.cover.style-hearts-cover{background:radial-gradient(circle at 20% 30%,rgba(255,105,180,.7) 0%,transparent 35%),radial-gradient(circle at 80% 70%,rgba(255,192,203,.65) 0%,transparent 35%),#1a0008;background-size:2000px 2000px,2000px 2000px,100% 100%;animation:coverPulse4k 8s ease infinite}
.cover.style-stars-cover{background:radial-gradient(circle at 15% 25%,#fff 2px,transparent 3px),radial-gradient(circle at 65% 75%,#fff 2px,transparent 3px),#000020;background-size:130px 130px,150px 150px,100% 100%;animation:starsDrift 22s linear infinite}
.cover.style-bubbles-cover{background:radial-gradient(circle at 10% 30%,rgba(255,255,255,.5) 0%,transparent 8%),linear-gradient(180deg,#0a1535,#1a2a5a);background-size:200px 200px,100% 100%;animation:snowDrift 25s linear infinite}
.cover.style-sunset{background:linear-gradient(180deg,#ff6b35 0%,#f7931e 30%,#ff006e 60%,#8338ec 100%);animation:coverPulse4k 7s ease-in-out infinite}
.cover.style-ocean{background:linear-gradient(180deg,#001f3f 0%,#0074d9 40%,#39cccc 70%,#7fdbff 100%);animation:coverPulse4k 11s ease-in-out infinite}
.cover.style-forest{background:linear-gradient(180deg,#0a1a0a 0%,#1a4a1a 30%,#2d5a2d 60%,#0d2d0d 100%);background-size:2000px 2000px;animation:fog4k 16s ease infinite}
.cover.style-pink-dream{background:linear-gradient(135deg,#ffc0cb,#ff69b4,#da70d6,#9370db);background-size:2000px 2000px;animation:fog4k 10s ease infinite}
.cover.style-rose-garden{background:radial-gradient(circle at 20% 30%,rgba(255,105,180,.8) 0%,transparent 40%),radial-gradient(circle at 80% 70%,rgba(255,192,203,.7) 0%,transparent 40%),linear-gradient(135deg,#ffb6c1,#ff69b4);animation:coverPulse4k 8s ease infinite}
.cover.style-glitter-pink{background:radial-gradient(circle at 10% 20%,#fff 1px,transparent 2px),radial-gradient(circle at 40% 60%,#fff 1px,transparent 2px),linear-gradient(135deg,#ff69b4,#da70d6);background-size:60px 60px,80px 80px,100% 100%;animation:snowDrift 20s linear infinite}
.cover.style-doll-room{background:linear-gradient(135deg,#ffd1dc,#f8bbd0,#e1bee7,#ce93d8);animation:coverPulse4k 9s ease infinite}
.cover.style-lavender{background:linear-gradient(135deg,#e6e6fa,#dda0dd,#9370db);animation:fog4k 12s ease infinite}
.cover.style-butterfly-cover{background:radial-gradient(circle at 25% 25%,rgba(255,182,193,.7) 0%,transparent 35%),radial-gradient(circle at 75% 75%,rgba(218,112,214,.7) 0%,transparent 35%),#fff0f5;animation:coverPulse4k 10s ease infinite}
.click-ripple{position:fixed;border-radius:50%;pointer-events:none;z-index:150;transform:translate(-50%,-50%) scale(0);animation:clickRippleAnim .7s cubic-bezier(.2,.6,.4,1) forwards}
.click-ripple.ripple{background:radial-gradient(circle,var(--red-soft) 0%,transparent 70%);border:2px solid var(--red-line)}
.click-ripple.glow{background:radial-gradient(circle,var(--red) 0%,transparent 70%);border:none;filter:blur(6px)}
.click-ripple.pulse{background:transparent;border:2px solid var(--red);box-shadow:0 0 22px var(--red)}
.click-ripple.gold{background:radial-gradient(circle,rgba(255,215,0,.65) 0%,transparent 70%);border:2px solid rgba(255,215,0,.95)}
.click-ripple.rainbow{background:conic-gradient(from 0deg,#ff3b30,#ff9500,#ffcc00,#34c759,#007aff,#5856d6,#af52de,#ff3b30);border:none;filter:blur(2px)}
@keyframes clickRippleAnim{0%{transform:translate(-50%,-50%) scale(0);opacity:1}100%{transform:translate(-50%,-50%) scale(4);opacity:0}}
.emoji-click{position:fixed;pointer-events:none;z-index:150;font-size:40px;line-height:1;transform:translate(-50%,-50%);animation:emojiClickAnim 1s cubic-bezier(.2,.6,.4,1) forwards;filter:drop-shadow(0 3px 10px rgba(0,0,0,.35))}
@keyframes emojiClickAnim{0%{opacity:0;transform:translate(-50%,-50%) scale(.3) rotate(-30deg)}25%{opacity:1;transform:translate(-50%,-50%) scale(1.3) rotate(15deg)}100%{opacity:0;transform:translate(-50%,-160%) scale(.85) rotate(-10deg)}}
@media (max-width:1120px){.layout{grid-template-columns:220px minmax(0,1fr)}.right{display:none}}
@media (max-width:820px){.layout{grid-template-columns:minmax(0,1fr);padding:14px}.left{display:none}.search{max-width:none}.logo-text{display:none}.player-track{width:auto;flex:1}.player-bar{display:none}.player-time{display:none}}
</style>
</head>
<body>
<div class="toast-container" id="toastContainer"></div>
<button class="dev-toggle-btn" id="devToggleBtn" title="Dev Panel">🔧</button>
<header>
  <div class="header-inner">
    <div class="logo" id="logoBtn"><div class="logo-mark">VK</div><div class="logo-text">Vkontakte <span>Visual</span></div></div>
    <div class="search"><svg width="17" height="17" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><circle cx="11" cy="11" r="7"/><path d="M20 20l-3.5-3.5"/></svg><input type="text" id="searchInput" placeholder="Поиск" autocomplete="off"></div>
    <nav class="header-nav">
      <button class="icon-btn" title="Сообщения" data-view="messages"><svg width="21" height="21" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8"><path d="M21 11.5a8.4 8.4 0 0 1-9 8.4 9 9 0 0 1-3.8-.9L3 20.5l1.5-4.6A8.4 8.4 0 0 1 3.6 11.5a8.4 8.4 0 0 1 8.4-8.4h.5a8.4 8.4 0 0 1 8.5 8.4z"/></svg></button>
      <div class="header-av" id="headerAvatar" data-view="profile"></div>
    </nav>
  </div>
</header>
<div class="layout">
  <aside class="left">
    <div class="card menu" id="mainMenu">
      <a href="#" class="menu-item" data-view="profile">🏠 Моя страница</a>
      <a href="#" class="menu-item active" data-view="home">📰 Новости</a>
      <a href="#" class="menu-item" data-view="messages">💬 Мессенджер</a>
      <a href="#" class="menu-item" data-view="friends">👥 Друзья</a>
      <a href="#" class="menu-item" data-view="people">🌍 Люди</a>
      <a href="#" class="menu-item" data-view="communities">🌐 Сообщества</a>
      <a href="#" class="menu-item" data-view="music">🎵 Музыка</a>
      <a href="#" class="menu-item" data-view="games">🎮 Игры</a>
      <a href="#" class="menu-item" data-view="stickers">🖼 Стикеры<span class="badge" id="stickersBadge">0</span></a>
      <a href="#" class="menu-item" data-view="codes">🎁 Code</a>
      <a href="#" class="menu-item" data-view="market">🛒 Маркет</a>
      <a href="#" class="menu-item" data-view="gallery">🖼 Галерея</a>
      <div class="menu-sep"></div>
      <a href="#" class="menu-item" data-view="bookmarks">🔖 Закладки</a>
      <a href="#" class="menu-item" data-view="settings">⚙️ Настройки</a>
    </div>
    <div class="left-footer">Vkontakte Visual © 2025</div>
  </aside>
  <main class="feed" id="main"></main>
  <aside class="right" id="rightSide"></aside>
</div>
<div class="player" id="player"></div>

<div class="modal-backdrop" id="modal" hidden>
  <div class="modal">
    <div class="modal-head"><h2>Редактировать профиль</h2><button class="row-btn" id="modalClose">✕</button></div>
    <div class="modal-body">
      <div style="display:flex;align-items:center;gap:16px;padding:14px;background:var(--surface-2);border-radius:14px">
        <div class="avatar-wrap" id="avatarPreviewWrap" style="padding:4px;background:var(--surface);border-radius:50%">
          <div class="avatar a58" id="avatarPreview">??</div>
        </div>
        <div style="flex:1;display:flex;flex-direction:column;gap:8px">
          <label class="btn-primary" style="cursor:pointer;text-align:center;padding:10px 18px;display:flex;align-items:center;justify-content:center;gap:6px">📷 Загрузить фото<input type="file" id="avatarPhotoInput" accept="image/*" style="display:none"></label>
          <button type="button" class="btn-ghost" id="avatarPhotoRemove" style="padding:8px 16px;font-size:13px">Убрать фото</button>
        </div>
      </div>
      <label class="field"><span>Имя</span><input id="fName" maxlength="40"></label>
      <label class="field"><span>Статус</span><input id="fStatus" maxlength="80"></label>
      <label class="field"><span>Город</span><input id="fCity" maxlength="40"></label>
      <label class="field"><span>Телефон</span><input id="fPhone" maxlength="30"></label>
      <label class="field"><span>Email</span><input id="fEmail" type="email" maxlength="60"></label>
      <label class="field"><span>О себе</span><textarea id="fAbout" rows="3" maxlength="240"></textarea></label>
      <div class="field"><span>🎨 Эффект аватарки</span><div id="avatarStylePicker" style="display:grid;grid-template-columns:repeat(4,1fr);gap:6px;max-height:200px;overflow-y:auto"></div></div>
      <div class="field"><span>🌄 Фон профиля</span><div id="coverStylePicker" style="display:grid;grid-template-columns:repeat(4,1fr);gap:6px;max-height:200px;overflow-y:auto"></div></div>
      <label class="field"><span>Кто вы (роль)</span><div id="rolePicker" style="display:grid;grid-template-columns:1fr 1fr;gap:8px"></div></label>
      <div style="padding-top:14px;border-top:1px solid var(--border-soft);margin-top:6px">
        <button id="deleteMyAccountBtn" style="width:100%;padding:12px;border-radius:11px;background:transparent;border:1px solid var(--red-line);color:var(--red);font-weight:700;font-size:13.5px;cursor:pointer">🗑 Удалить мой аккаунт</button>
      </div>
    </div>
    <div class="modal-foot"><button class="btn-ghost" id="modalCancel">Отмена</button><button class="btn-primary" id="modalSave">Сохранить</button></div>
  </div>
</div>

<div class="modal-backdrop" id="stickerPickerModal" hidden><div class="modal" style="max-width:680px"><div class="modal-head"><h2>😊 Выбрать стикер</h2><button class="row-btn" id="stickerPickerClose">✕</button></div><div style="padding:20px 22px;overflow-y:auto;max-height:72vh" id="stickerPickerBody"></div></div></div>

<div class="modal-backdrop" id="genderModal" hidden><div class="modal" style="max-width:480px"><div class="modal-head"><h2>👋 Кто вы?</h2></div><div class="modal-body"><div style="display:grid;grid-template-columns:1fr 1fr;gap:12px"><button class="theme-btn" data-gender="girl" style="flex-direction:column;padding:18px 14px"><div style="font-size:36px">👧</div><div style="font-size:15px;font-weight:700">Девочка</div></button><button class="theme-btn" data-gender="boy" style="flex-direction:column;padding:18px 14px"><div style="font-size:36px">👦</div><div style="font-size:15px;font-weight:700">Мальчик</div></button><button class="theme-btn" data-gender="child" style="flex-direction:column;padding:18px 14px"><div style="font-size:36px">🍼</div><div style="font-size:15px;font-weight:700">Ребёнок</div></button><button class="theme-btn" data-gender="unknown" style="flex-direction:column;padding:18px 14px"><div style="font-size:36px">🕵️</div><div style="font-size:15px;font-weight:700">Скрыть</div></button></div></div></div></div>

<div class="modal-backdrop" id="registrationModal" hidden>
  <div class="modal" style="max-width:500px">
    <div class="modal-head"><h2>👋 Регистрация в VK Visual</h2></div>
    <div class="modal-body">
      <p style="color:var(--muted);font-size:13px;text-align:center;margin-bottom:10px">Создайте аккаунт — это займёт 30 секунд</p>
      <div class="reg-tabs"><button class="reg-tab active" data-reg-tab="phone">📱 Телефон</button><button class="reg-tab" data-reg-tab="gmail">📧 Gmail</button></div>
      <div id="regPhoneSection" class="reg-step">
        <label class="field"><span>Номер телефона</span><input id="regPhone" type="tel" placeholder="+7 (999) 123-45-67"></label>
        <button class="btn-primary" id="regPhoneSend">📩 Отправить код</button>
        <div id="regPhoneCodeStep" class="reg-step" hidden>
          <label class="field"><span>Код из SMS</span><input id="regPhoneCode" type="text" placeholder="1234" maxlength="4" style="font-size:20px;letter-spacing:6px;text-align:center;font-weight:800"></label>
          <div class="reg-code-hint">Демо-код: <b>1234</b></div>
          <button class="btn-primary" id="regPhoneVerify">✅ Подтвердить</button>
        </div>
      </div>
      <div id="regGmailSection" class="reg-step" hidden>
        <label class="field"><span>Gmail</span><input id="regGmail" type="email" placeholder="you@gmail.com"></label>
        <button class="btn-primary" id="regGmailSend">📩 Отправить код</button>
        <div id="regGmailCodeStep" class="reg-step" hidden>
          <label class="field"><span>Код из письма</span><input id="regGmailCode" type="text" placeholder="1234" maxlength="4" style="font-size:20px;letter-spacing:6px;text-align:center;font-weight:800"></label>
          <div class="reg-code-hint">Демо-код: <b>1234</b></div>
          <button class="btn-primary" id="regGmailVerify">✅ Подтвердить</button>
        </div>
      </div>
      <div id="regNameStep" class="reg-step" hidden>
        <label class="field"><span>Ваше имя</span><input id="regName" placeholder="Иван Иванов" maxlength="40"></label>
        <label class="field"><span>Ваш пол</span>
          <div style="display:grid;grid-template-columns:1fr 1fr;gap:8px">
            <button class="theme-btn" data-reg-gender="girl" style="flex-direction:column;padding:12px 8px"><div style="font-size:26px">👧</div><div style="font-size:12px;font-weight:700">Девочка</div></button>
            <button class="theme-btn" data-reg-gender="boy" style="flex-direction:column;padding:12px 8px"><div style="font-size:26px">👦</div><div style="font-size:12px;font-weight:700">Мальчик</div></button>
            <button class="theme-btn" data-reg-gender="child" style="flex-direction:column;padding:12px 8px"><div style="font-size:26px">🍼</div><div style="font-size:12px;font-weight:700">Ребёнок</div></button>
            <button class="theme-btn" data-reg-gender="unknown" style="flex-direction:column;padding:12px 8px"><div style="font-size:26px">🕵️</div><div style="font-size:12px;font-weight:700">Скрыть</div></button>
          </div>
        </label>
        <button class="btn-primary" id="regFinish">🚀 Завершить регистрацию</button>
      </div>
      <div style="text-align:center;padding-top:14px;border-top:1px solid var(--border-soft);margin-top:6px">
        <button id="regLoginAsAdmin" style="font-size:12px;color:var(--muted-2);background:none;border:none;cursor:pointer;padding:6px">🔑 Войти как Admin (V1LARD)</button>
      </div>
    </div>
  </div>
</div>

<div class="modal-backdrop" id="ideaModal" hidden><div class="modal" style="max-width:520px"><div class="modal-head"><h2>💡 Идея для проекта</h2><button class="row-btn" id="ideaClose">✕</button></div><div class="modal-body"><label class="field"><span>Ваша идея</span><textarea id="ideaText" rows="6" maxlength="500"></textarea></label><div style="font-size:11.5px;color:var(--muted-2);text-align:right" id="ideaCounter">0/500</div></div><div class="modal-foot"><button class="btn-ghost" id="ideaCancel">Отмена</button><button class="btn-primary" id="ideaSend">📨 Отправить</button></div></div></div>

<div class="modal-backdrop" id="newAccountModal" hidden><div class="modal" style="max-width:500px"><div class="modal-head"><h2>➕ Создать новый аккаунт</h2><button class="row-btn" id="newAccClose">✕</button></div><div class="modal-body"><label class="field"><span>Имя</span><input id="newAccName" maxlength="40"></label><label class="field"><span>Номер телефона</span><input id="newAccPhone" type="tel"></label><label class="field"><span>Email</span><input id="newAccEmail" type="email"></label><label class="field"><span>Пароль</span><input id="newAccPassword" type="password"></label><label class="field"><span>Ваш пол</span><div style="display:grid;grid-template-columns:1fr 1fr;gap:8px"><button class="theme-btn" data-newacc-gender="girl" style="flex-direction:column;padding:12px 8px"><div style="font-size:26px">👧</div><div style="font-size:12px;font-weight:700">Девочка</div></button><button class="theme-btn" data-newacc-gender="boy" style="flex-direction:column;padding:12px 8px"><div style="font-size:26px">👦</div><div style="font-size:12px;font-weight:700">Мальчик</div></button><button class="theme-btn" data-newacc-gender="child" style="flex-direction:column;padding:12px 8px"><div style="font-size:26px">🍼</div><div style="font-size:12px;font-weight:700">Ребёнок</div></button><button class="theme-btn" data-newacc-gender="unknown" style="flex-direction:column;padding:12px 8px"><div style="font-size:26px">🕵️</div><div style="font-size:12px;font-weight:700">Скрыть</div></button></div></label></div><div class="modal-foot"><button class="btn-ghost" id="newAccCancel">Отмена</button><button class="btn-primary" id="newAccCreate">Создать</button></div></div></div>

<div class="modal-backdrop" id="accountsModal" hidden><div class="modal" style="max-width:500px"><div class="modal-head"><h2>👥 Мои аккаунты</h2><button class="row-btn" id="accountsClose">✕</button></div><div class="modal-body" id="accountsList" style="gap:6px"></div></div></div>

<div class="modal-backdrop" id="paymentModal" hidden><div class="modal pay-modal"><div class="modal-head" style="display:flex;align-items:center;gap:14px;justify-content:flex-start"><button class="pay-back-btn" id="payBackBtn">← Назад</button><h2 id="payModalTitle" style="flex:1;margin:0">💳 Оплата</h2><button class="row-btn" id="payClose">✕</button></div><div class="modal-body" id="payBody"></div></div></div>

<div class="modal-backdrop" id="notifPermissionModal" hidden><div class="modal notif-modal"><div class="notif-hero"><div class="notif-logo">VK</div><div class="notif-app">VK Visual</div></div><div class="notif-title">Разрешить уведомления?</div><div class="notif-desc">VK Visual хочет присылать уведомления о новых сообщениях. Также включим звук.</div><div class="notif-actions"><button class="notif-btn notif-btn-deny" id="notifDeny">Запретить</button><button class="notif-btn notif-btn-allow" id="notifAllow">Разрешить</button></div><div class="notif-hint">Окно появится <b>только один раз</b>.</div></div></div>

<div class="modal-backdrop" id="micPermissionModal" hidden><div class="modal notif-modal"><div class="notif-hero"><div class="notif-logo">🎤</div><div class="notif-app">Микрофон</div></div><div class="notif-title">Разрешить микрофон?</div><div class="notif-desc">Для отправки голосовых сообщений нужен доступ к микрофону.</div><div class="notif-actions"><button class="notif-btn notif-btn-deny" id="micDeny">Запретить</button><button class="notif-btn notif-btn-allow" id="micAllow">Разрешить</button></div><div class="notif-hint">Вы можете изменить это позже в настройках браузера.</div></div></div>

<div class="modal-backdrop" id="devPassModal" hidden><div class="modal" style="max-width:420px"><div class="modal-head"><h2>🔐 Пароль разработчика</h2><button class="row-btn" id="devPassClose">✕</button></div><div class="modal-body"><label class="field"><span>Пароль</span><input id="devPassInput" type="password" placeholder="По умолчанию admin"></label><div id="devPassError" style="color:var(--red);font-size:12.5px;display:none">❌ Неверный пароль</div></div><div class="modal-foot"><button class="btn-ghost" id="devPassCancel">Отмена</button><button class="btn-primary" id="devPassOk">Войти</button></div></div></div>

<div class="modal-backdrop" id="chatModal" hidden><div class="modal" style="max-width:520px;height:70vh;display:flex;flex-direction:column"><div class="modal-head"><h2 id="chatTitle">Чат</h2><button class="row-btn" id="chatClose">✕</button></div><div class="modal-body" id="chatBody" style="flex:1;overflow-y:auto;display:flex;flex-direction:column;gap:8px;min-height:200px"></div><div id="chatEmojiPanel" style="display:none;padding:8px 12px;border-top:1px solid var(--border-soft);flex-wrap:wrap;gap:4px;max-height:120px;overflow-y:auto"></div><div class="modal-foot" style="gap:8px;align-items:center"><input id="chatInput" placeholder="Сообщение..." style="flex:1;padding:10px 14px;border-radius:10px;background:var(--surface-2);border:1px solid var(--border);color:var(--text);outline:none;font-size:13.5px"><button id="chatEmojiBtn" title="Смайлики" style="width:42px;height:42px;border-radius:50%;background:var(--surface-2);border:1px solid var(--border);color:var(--text);font-size:18px;cursor:pointer;flex-shrink:0">😊</button><button id="chatVoiceBtn" title="Голосовое сообщение" style="width:42px;height:42px;border-radius:50%;background:var(--surface-2);border:1px solid var(--border);color:var(--text);font-size:18px;cursor:pointer;flex-shrink:0">🎤</button><button class="btn-primary" id="chatSend">Отправить</button></div></div></div>

<div class="modal-backdrop" id="confirmDeleteModal" hidden><div class="modal" style="max-width:420px"><div class="modal-head"><h2 style="color:var(--red)">🗑 Удалить аккаунт?</h2></div><div class="modal-body"><p style="font-size:14px;line-height:1.6">Аккаунт <b id="deleteAccName">—</b> будет удалён безвозвратно. Все посты, друзья, сообщения и покупки будут потеряны.</p><p style="font-size:12.5px;color:var(--muted-2)">Введите имя аккаунта для подтверждения:</p><input id="deleteConfirmInput" placeholder="Имя аккаунта" style="padding:11px 14px;border-radius:11px;background:var(--surface-2);border:1px solid var(--border);color:var(--text);font-size:14px;outline:none"></div><div class="modal-foot"><button class="btn-ghost" id="confirmDeleteCancel">Отмена</button><button class="btn-primary" id="confirmDeleteOk" style="background:linear-gradient(135deg,#ff3b30,#a51f16)">🗑 Удалить</button></div></div></div>

<div class="gallery-viewer" id="galleryViewer" hidden><button class="gv-close" id="gvClose">✕</button><img id="gvImg" src="" alt=""></div>

<div class="dev-banned-overlay" id="bannedOverlay" hidden>
  <div class="dev-banned-icon">🚫</div>
  <div class="dev-banned-title">Вы заблокированы</div>
  <div style="display:flex;gap:10px;flex-wrap:wrap;justify-content:center;margin-top:20px">
    <button id="bannedUnbanBtn" style="padding:14px 28px;font-size:15px;font-weight:700;border-radius:12px;background:linear-gradient(135deg,#22a355,#16a34a);color:#fff;border:none;cursor:pointer;box-shadow:0 8px 24px rgba(34,163,85,.4)">🔓 Разбанить</button>
    <button id="bannedResetBtn" style="padding:14px 28px;font-size:15px;font-weight:700;border-radius:12px;background:linear-gradient(135deg,#ff3b30,#d42a22);color:#fff;border:none;cursor:pointer;box-shadow:0 8px 24px rgba(255,59,48,.4)">🧹 Полный сброс</button>
  </div>
</div>

<div class="dev-panel-backdrop" id="devPanelBackdrop" hidden><div class="dev-panel"><div class="dev-head"><h2>🛠 Developer Panel <span class="dev-tag">DEV</span></h2><button class="row-btn" id="devClose">✕</button></div><div class="dev-body"><div class="dev-section"><div class="dev-section-title">📊 Статус</div><div class="dev-row"><span class="dev-label">BkV:</span><span class="dev-val" id="devBalance">0</span><span class="dev-label">🎙:</span><span class="dev-val" id="devVoices">0</span></div><div class="dev-row"><span class="dev-label">VIP:</span><span class="dev-val" id="devVIPStatus">Нет</span></div></div><div class="dev-section"><div class="dev-section-title">👤 Пол</div><div class="dev-row"><button class="dev-btn-sm" data-set-gender="girl">👧</button><button class="dev-btn-sm" data-set-gender="boy">👦</button><button class="dev-btn-sm" data-set-gender="child">🍼</button><button class="dev-btn-sm" data-set-gender="unknown">🕵️</button></div></div><div class="dev-section"><div class="dev-section-title">💰 BkV</div><div class="dev-row"><button class="dev-btn-sm primary" data-give="100">+100</button><button class="dev-btn-sm primary" data-give="1000">+1000</button><button class="dev-btn-sm primary" data-give="10000">+10000</button></div><div class="dev-row"><input class="dev-input" id="devSetCoinsInput" type="number"><button class="dev-btn-sm" id="devSetCoinsBtn">Задать</button></div></div><div class="dev-section"><div class="dev-section-title">🎙 Голоса</div><div class="dev-row"><button class="dev-btn-sm primary" data-give-voice="10">+10</button><button class="dev-btn-sm primary" data-give-voice="50">+50</button><button class="dev-btn-sm primary" data-give-voice="100">+100</button></div><div class="dev-row"><input class="dev-input" id="devSetVoicesInput" type="number"><button class="dev-btn-sm" id="devSetVoicesBtn">Задать</button></div><div class="dev-row"><button class="dev-btn-sm success" id="devUnlockAllStickers">Все стикеры</button></div></div><div class="dev-section"><div class="dev-section-title">👑 VIP</div><div class="dev-row"><button class="dev-btn-sm vip" data-vip-give="30">+30д</button><button class="dev-btn-sm vip" data-vip-give="365">+1г</button><button class="dev-btn-sm vip" data-vip-give="99999">∞</button><button class="dev-btn-sm danger" id="devVIPRemove">Забрать</button><button class="dev-btn-sm success" id="devVIPRestore">Восстановить</button></div></div><div class="dev-section"><div class="dev-section-title">👑 Admin</div><div class="dev-row"><button class="dev-btn-sm success" id="devAdminGive">Выдать Admin</button><button class="dev-btn-sm danger" id="devAdminRemove">Снять Admin</button></div></div><div class="dev-section"><div class="dev-section-title">👤 Снять админку у пользователя</div><div class="dev-row"><input class="dev-input" id="devRemoveAdminId" placeholder="ID аккаунта (телефон/email)"><button class="dev-btn-sm danger" id="devRemoveAdminById">Снять</button></div></div><div class="dev-section"><div class="dev-section-title">🚫</div><div class="dev-row"><button class="dev-btn-sm danger" id="devBanBtn">Забанить</button><button class="dev-btn-sm success" id="devUnbanBtn">Разбанить</button></div></div><div class="dev-section"><div class="dev-section-title">🔑 Аккаунт</div><div class="dev-row"><button class="dev-btn-sm success" id="devLoginV1LARD">👑 Войти как V1LARD</button><button class="dev-btn-sm danger" id="devLogout">🚪 Выйти (на регистрацию)</button></div></div><div class="dev-section"><div class="dev-section-title">⚠️</div><div class="dev-row"><button class="dev-btn-sm danger" id="devResetAll">Полный сброс</button></div></div></div></div></div>

<script>
/* === SAFE WRAPPER === */
function safe(fn){try{return fn()}catch(e){console.error('[safe]',e);return null}}
window.addEventListener('error',e=>{console.error('[global]',e.error||e.message)});

/* === КОНСТАНТЫ === */
const ROLES=[
  {id:'youtuber',name:'Ютубер',emoji:'📹',bg:'linear-gradient(135deg,#ff0000,#cc0000)',color:'#fff'},
  {id:'tiktoker',name:'Тиктокер',emoji:'🎵',bg:'linear-gradient(135deg,#222,#000)',color:'#fff',border:'1.5px solid #555'},
  {id:'twitch',name:'Твич',emoji:'🟣',bg:'linear-gradient(135deg,#9146ff,#6441a5)',color:'#fff'},
  {id:'singer',name:'Певец',emoji:'🎤',bg:'linear-gradient(135deg,#ff9500,#ff6600)',color:'#fff'}
];
const VIP_PRICES={30:{rub:10000,coins:15000,label:'30 дней'},365:{rub:20000,coins:30000,label:'1 год'},99999:{rub:50000,coins:75000,label:'Навсегда'}};
const DAY_MS=24*60*60*1000;
const COIN_PACKS=[{id:'pack10',coins:10,price:500,label:'Старт'},{id:'pack100',coins:100,price:1000,label:'Популярный',featured:true},{id:'pack500',coins:500,price:5000,label:'Средний'},{id:'pack1000',coins:1000,price:9000,label:'Большой'},{id:'pack5000',coins:5000,price:15000,label:'Максимум'}];
const STICKER_PACKS=[
  {id:'red_basic',name:'Красный классик',price:5,theme:'red',cover:'❤️',stickers:['❤️','🔥','💢','💥','⚡','🩸','💯','💔']},
  {id:'black_basic',name:'Чёрный минимал',price:5,theme:'black',cover:'🖤',stickers:['🖤','💀','☠️','🕷️','🕸️','🌑','⚫','◾']},
  {id:'red_love',name:'Красная любовь',price:7,theme:'red',cover:'💘',stickers:['💘','💝','💖','💗','💓','💞','💕','❤️‍🔥']},
  {id:'black_goth',name:'Готика',price:7,theme:'black',cover:'🥀',stickers:['🥀','🦇','🕯️','⚰️','🔮','🗡️','⚔️','🪦']},
  {id:'red_rage',name:'Ярость',price:10,theme:'red',cover:'😡',stickers:['😡','🤬','💢','🔥','⚡','💥','🗯️','💣']},
  {id:'black_dark',name:'Тьма',price:10,theme:'black',cover:'😈',stickers:['😈','👿','💀','🎭','🕳️','🌚','🌑','🖤']},
  {id:'red_fire',name:'Огонь',price:6,theme:'red',cover:'🔥',stickers:['🔥','⚡','💥','💢','🎇','🎆','✴️','❇️']},
  {id:'black_moon',name:'Луна',price:6,theme:'black',cover:'🌑',stickers:['🌑','🌒','🌘','🌚','🌑','🖤','⭐','🌌']},
  {id:'red_sport',name:'Спорт',price:8,theme:'red',cover:'🏆',stickers:['⚽','🏀','🏈','🎯','🏆','🥇','🔥','💪']},
  {id:'black_tech',name:'Техно',price:8,theme:'black',cover:'💻',stickers:['💻','⌨️','🖥️','🖱️','📱','🔌','⚙️','🔋']},
  {id:'red_party',name:'Вечеринка',price:9,theme:'red',cover:'🎉',stickers:['🎉','🎊','🎈','🎁','🎂','🍾','🥂','✨']},
  {id:'black_music',name:'Музыка',price:9,theme:'black',cover:'🎵',stickers:['🎵','🎶','🎤','🎧','🎸','🎹','🥁','🎼']},
  {id:'red_food',name:'Еда',price:5,theme:'red',cover:'🍕',stickers:['🍎','🍕','🍔','🍟','🌮','🍣','🍰','🍩']},
  {id:'black_night',name:'Ночь',price:5,theme:'black',cover:'🌃',stickers:['🌃','🌉','🌌','⭐','🌙','✨','🖤','🌑']},
  {id:'red_animals',name:'Звери',price:7,theme:'red',cover:'🦁',stickers:['🦁','🐯','🐺','🐻','🦊','🐼','🐨','🦝']},
  {id:'black_horror',name:'Хоррор',price:8,theme:'black',cover:'👻',stickers:['👻','🎃','💀','🧟','🕷️','🕸️','⚰️','🩸']},
  {id:'red_fashion',name:'Мода',price:8,theme:'red',cover:'👑',stickers:['👗','👠','💄','💅','👑','💎','👜','💍']},
  {id:'black_retro',name:'Ретро',price:6,theme:'black',cover:'📼',stickers:['📼','📻','🎞️','📷','🎬','📺','☎️','💾']},
  {id:'red_weather',name:'Погода',price:6,theme:'red',cover:'☀️',stickers:['☀️','🌤️','⛅','🌧️','⛈️','❄️','🌈','🌪️']},
  {id:'black_cyber',name:'Киберпанк',price:10,theme:'black',cover:'🤖',stickers:['🤖','💻','🎮','🕹️','⚡','🔋','📡','🛸']},
  {id:'red_emotions',name:'Эмоции',price:7,theme:'red',cover:'😂',stickers:['😀','😂','😍','🥰','😎','🤩','🥳','😭']},
  {id:'black_zen',name:'Дзен',price:7,theme:'black',cover:'🧘',stickers:['🧘','☯️','🕉️','🔮','🌿','🍃','✨','💫']}
];
const PROMO_CODES={'VKVISUAL':{reward:{type:'voices',amount:100},desc:'100 голосов'},'WELCOME':{reward:{type:'bkv',amount:500},desc:'500 BkV'},'VIPFREE':{reward:{type:'vip',days:365},desc:'VIP на 1 год'},'STICKERS':{reward:{type:'random-pack'},desc:'Случайный стикерпак'},'REDCODE':{reward:{type:'voices',amount:50},desc:'50 голосов'},'BLACKCODE':{reward:{type:'voices',amount:50},desc:'50 голосов'},'ADMIN2026':{reward:{type:'bkv',amount:5000},desc:'5 000 BkV'},'PROMO100':{reward:{type:'bkv',amount:1000},desc:'1 000 BkV'},'VOICES50':{reward:{type:'voices',amount:50},desc:'50 голосов'},'VKBONUS':{reward:{type:'bkv',amount:100},desc:'100 BkV'},'VIP2026':{reward:{type:'vip',days:30},desc:'VIP на 30 дней'},'STICKERKING':{reward:{type:'all-packs'},desc:'Все стикерпаки'}};
const music=[
{id:101,title:'Blinding Lights',artist:'The Weeknd',dur:200,quality:'4K'},{id:102,title:'Save Your Tears',artist:'The Weeknd',dur:215,quality:'4K'},{id:103,title:'Starboy',artist:'The Weeknd',dur:230,quality:'Hi-Res'},{id:104,title:'Die For You',artist:'The Weeknd',dur:260,quality:'4K'},{id:105,title:"Can't Feel My Face",artist:'The Weeknd',dur:213,quality:'4K'},{id:106,title:'Anti-Hero',artist:'Taylor Swift',dur:200,quality:'4K'},{id:107,title:'Shake It Off',artist:'Taylor Swift',dur:219,quality:'Hi-Res'},{id:108,title:'Blank Space',artist:'Taylor Swift',dur:231,quality:'4K'},{id:109,title:'Cruel Summer',artist:'Taylor Swift',dur:178,quality:'4K'},{id:110,title:'Love Story',artist:'Taylor Swift',dur:235,quality:'Lossless'},{id:111,title:"God's Plan",artist:'Drake',dur:198,quality:'4K'},{id:112,title:'Hotline Bling',artist:'Drake',dur:267,quality:'Hi-Res'},{id:113,title:'One Dance',artist:'Drake',dur:173,quality:'4K'},{id:114,title:'7 rings',artist:'Ariana Grande',dur:178,quality:'4K'},{id:115,title:'thank u, next',artist:'Ariana Grande',dur:207,quality:'Hi-Res'},{id:116,title:'positions',artist:'Ariana Grande',dur:172,quality:'4K'},{id:117,title:'Shape of You',artist:'Ed Sheeran',dur:234,quality:'4K'},{id:118,title:'Perfect',artist:'Ed Sheeran',dur:263,quality:'Lossless'},{id:119,title:'Bad Habits',artist:'Ed Sheeran',dur:231,quality:'4K'},{id:120,title:'bad guy',artist:'Billie Eilish',dur:194,quality:'4K'},{id:121,title:'Therefore I Am',artist:'Billie Eilish',dur:174,quality:'Hi-Res'},{id:122,title:'What Was I Made For?',artist:'Billie Eilish',dur:222,quality:'Dolby Atmos'},{id:123,title:'Levitating',artist:'Dua Lipa',dur:203,quality:'4K'},{id:124,title:"Don't Start Now",artist:'Dua Lipa',dur:183,quality:'4K'},{id:125,title:'Houdini',artist:'Dua Lipa',dur:185,quality:'Hi-Res'},{id:126,title:'Sunflower',artist:'Post Malone & Swae Lee',dur:158,quality:'4K'},{id:127,title:'Circles',artist:'Post Malone',dur:215,quality:'Hi-Res'},{id:128,title:'rockstar',artist:'Post Malone',dur:218,quality:'4K'},{id:129,title:'drivers license',artist:'Olivia Rodrigo',dur:242,quality:'4K'},{id:130,title:'good 4 u',artist:'Olivia Rodrigo',dur:178,quality:'4K'},{id:131,title:'vampire',artist:'Olivia Rodrigo',dur:219,quality:'Hi-Res'},{id:132,title:'Peaches',artist:'Justin Bieber',dur:198,quality:'4K'},{id:133,title:'Stay',artist:'The Kid LAROI & Justin Bieber',dur:141,quality:'4K'},{id:134,title:'Ghost',artist:'Justin Bieber',dur:153,quality:'Hi-Res'},{id:135,title:'Tití Me Preguntó',artist:'Bad Bunny',dur:243,quality:'4K'},{id:136,title:'Monaco',artist:'Bad Bunny',dur:247,quality:'Hi-Res'},{id:137,title:'Dynamite',artist:'BTS',dur:199,quality:'4K'},{id:138,title:'Butter',artist:'BTS',dur:164,quality:'Hi-Res'},{id:139,title:'Paint The Town Red',artist:'Doja Cat',dur:231,quality:'4K'},{id:140,title:'Kiss Me More',artist:'Doja Cat ft. SZA',dur:208,quality:'Hi-Res'},{id:141,title:'Kill Bill',artist:'SZA',dur:153,quality:'4K'},{id:142,title:'Snooze',artist:'SZA',dur:201,quality:'Hi-Res'},{id:143,title:'Flowers',artist:'Miley Cyrus',dur:200,quality:'4K'},{id:144,title:'Wrecking Ball',artist:'Miley Cyrus',dur:221,quality:'Lossless'},{id:145,title:'Espresso',artist:'Sabrina Carpenter',dur:175,quality:'4K'},{id:146,title:'Please Please Please',artist:'Sabrina Carpenter',dur:186,quality:'Hi-Res'},{id:147,title:'Just The Way You Are',artist:'Bruno Mars',dur:220,quality:'Lossless'},{id:148,title:'Uptown Funk',artist:'Mark Ronson ft. Bruno Mars',dur:270,quality:'4K'},{id:149,title:'Locked Out of Heaven',artist:'Bruno Mars',dur:233,quality:'4K'},{id:150,title:'Yellow',artist:'Coldplay',dur:266,quality:'Lossless'},{id:151,title:'Viva La Vida',artist:'Coldplay',dur:242,quality:'4K'},{id:152,title:'Fix You',artist:'Coldplay',dur:295,quality:'Hi-Res'},{id:153,title:'Bohemian Rhapsody',artist:'Queen',dur:355,quality:'Lossless'},{id:154,title:"Don't Stop Me Now",artist:'Queen',dur:209,quality:'Hi-Res'},{id:155,title:'Billie Jean',artist:'Michael Jackson',dur:294,quality:'Lossless'},{id:156,title:'Beat It',artist:'Michael Jackson',dur:258,quality:'4K'},{id:157,title:'Thriller',artist:'Michael Jackson',dur:357,quality:'Hi-Res'},{id:158,title:'Bad Romance',artist:'Lady Gaga',dur:294,quality:'4K'},{id:159,title:'Shallow',artist:'Lady Gaga & Bradley Cooper',dur:216,quality:'Lossless'},{id:160,title:'Poker Face',artist:'Lady Gaga',dur:237,quality:'Hi-Res'},{id:161,title:'Umbrella',artist:'Rihanna ft. JAY-Z',dur:275,quality:'4K'},{id:162,title:'Diamonds',artist:'Rihanna',dur:225,quality:'Hi-Res'},{id:163,title:'Work',artist:'Rihanna ft. Drake',dur:219,quality:'4K'},{id:164,title:'Halo',artist:'Beyoncé',dur:261,quality:'Lossless'},{id:165,title:'Single Ladies',artist:'Beyoncé',dur:193,quality:'Hi-Res'},{id:166,title:'Lose Yourself',artist:'Eminem',dur:326,quality:'Lossless'},{id:167,title:'Stan',artist:'Eminem ft. Dido',dur:404,quality:'Hi-Res'},{id:168,title:'Without Me',artist:'Eminem',dur:290,quality:'4K'},{id:169,title:'HUMBLE.',artist:'Kendrick Lamar',dur:177,quality:'4K'},{id:170,title:'Not Like Us',artist:'Kendrick Lamar',dur:274,quality:'4K'},{id:171,title:'Money Trees',artist:'Kendrick Lamar',dur:386,quality:'Hi-Res'},{id:172,title:'SICKO MODE',artist:'Travis Scott',dur:312,quality:'4K'},{id:173,title:'Goosebumps',artist:'Travis Scott',dur:243,quality:'Hi-Res'},{id:174,title:'Stronger',artist:'Kanye West',dur:312,quality:'Lossless'},{id:175,title:'Heartless',artist:'Kanye West',dur:271,quality:'4K'},{id:176,title:'Believer',artist:'Imagine Dragons',dur:204,quality:'4K'},{id:177,title:'Thunder',artist:'Imagine Dragons',dur:187,quality:'Hi-Res'},{id:178,title:'Someone Like You',artist:'Adele',dur:285,quality:'Lossless'},{id:179,title:'Rolling in the Deep',artist:'Adele',dur:228,quality:'4K'},{id:180,title:'Easy On Me',artist:'Adele',dur:224,quality:'Hi-Res'},{id:181,title:'As It Was',artist:'Harry Styles',dur:167,quality:'4K'},{id:182,title:'Watermelon Sugar',artist:'Harry Styles',dur:174,quality:'Hi-Res'},{id:183,title:'MONTERO',artist:'Lil Nas X',dur:137,quality:'4K'},{id:184,title:'Industry Baby',artist:'Lil Nas X',dur:212,quality:'Hi-Res'},
{id:201,title:'Cadillac',artist:'Morgenshtern',dur:170,quality:'4K'},{id:202,title:'Ратататата',artist:'Morgenshtern',dur:163,quality:'Hi-Res'},{id:203,title:'Положение',artist:'Скриптонит',dur:213,quality:'4K'},{id:204,title:'Город под подошвой',artist:'Oxxxymiron',dur:265,quality:'Hi-Res'},{id:205,title:'Life',artist:'Zivert',dur:170,quality:'4K'},{id:206,title:'Credo',artist:'Zivert',dur:180,quality:'Hi-Res'},{id:207,title:'Captain',artist:'Miyagi & Andy Panda',dur:225,quality:'4K'},{id:208,title:'Utopia',artist:'Miyagi & Andy Panda',dur:230,quality:'Hi-Res'},{id:209,title:'Сансара',artist:'Баста',dur:270,quality:'Lossless'},{id:210,title:'Медлячок',artist:'Баста',dur:210,quality:'Hi-Res'},{id:211,title:'Будущий папа',artist:'Монеточка',dur:185,quality:'4K'},{id:212,title:'Каждый раз',artist:'Монеточка',dur:195,quality:'Hi-Res'},{id:213,title:'Ай',artist:'ЛСП',dur:190,quality:'4K'},{id:214,title:'Твой макияж',artist:'ЛСП',dur:200,quality:'Hi-Res'},{id:215,title:'Trap Luv',artist:'Big Baby Tape',dur:180,quality:'4K'},{id:216,title:'Gimme the Loot',artist:'Big Baby Tape',dur:195,quality:'Hi-Res'},{id:217,title:'AUTOMAT',artist:'Slava Marlow',dur:140,quality:'4K'},{id:218,title:'Снова я напиваюсь',artist:'Slava Marlow',dur:150,quality:'Hi-Res'},{id:221,title:'Розовое вино',artist:'Элджей & Feduk',dur:205,quality:'4K'},{id:222,title:'Every Day',artist:'Элджей',dur:190,quality:'Hi-Res'},{id:223,title:'Всё, что касается',artist:'Kizaru',dur:210,quality:'4K'},{id:224,title:'Мой друг',artist:'Kizaru',dur:195,quality:'Hi-Res'},{id:225,title:'Пуля-дура',artist:'Хаски',dur:220,quality:'Lossless'}
];
const GAMES_LIST=[{id:'2048',icon:'🎮',name:'2048',desc:'Соединяй плитки'},{id:'snake',icon:'🐍',name:'Змейка',desc:'Собирай еду'},{id:'memory',icon:'🃏',name:'Мемори',desc:'Найди пары'},{id:'simon',icon:'🎵',name:'Саймон',desc:'Повтори мелодию'},{id:'ttt',icon:'❌',name:'Крестики',desc:'Против ИИ'},{id:'mines',icon:'💣',name:'Сапёр',desc:'Найди мины'},{id:'tetris',icon:'🧱',name:'Тетрис',desc:'Складывай блоки'},{id:'breakout',icon:'🧨',name:'Арканоид',desc:'Разбей кирпичи'},{id:'reaction',icon:'⚡',name:'Реакция',desc:'Успей нажать'},{id:'guess',icon:'🔢',name:'Угадай',desc:'Число 1–100'}];
const posts=[
  {id:1,author:'VK Visual',initials:'VK',time:'сегодня',text:'🎉 Добро пожаловать в VK Visual! Регистрируйтесь, публикуйте посты, слушайте музыку.',sticker:'🎉',reactions:{'❤️':128},myReaction:null,comments:12,shares:5,mine:false},
  {id:2,author:'Команда VK',initials:'КV',time:'2 часа назад',text:'📹 Можно прикрепить к посту аудио или видео!',sticker:null,reactions:{'❤️':64},myReaction:null,comments:8,shares:3,mine:false}
];
const communities=[{initials:'VV',name:'Vkontakte Visual',sub:'128K',joined:true},{initials:'BW',name:'Black & White',sub:'64K',joined:true}];

const AVATAR_STYLES=[
  {id:'none',label:'Статика'},{id:'spin',label:'Вращение'},{id:'pulse',label:'Пульс'},{id:'wave',label:'Волна'},{id:'orbit',label:'Орбита'},
  {id:'glow',label:'Свечение'},{id:'ripple',label:'Волны'},{id:'neon',label:'Неон'},{id:'rainbow',label:'Радуга'},{id:'hearts',label:'Сердца'},
  {id:'flame',label:'Пламя'},{id:'galaxy-av',label:'Галактика'},{id:'ice',label:'Лёд'},{id:'diamond',label:'Бриллиант'},{id:'shadow',label:'Тень'},
  {id:'aurora-av',label:'Сияние'},{id:'sparkle-av',label:'Искры'},
  {id:'pink-glow',label:'Роз.свечение'},{id:'rose-frame',label:'Розы'},{id:'glitter-heart',label:'Блёстки'},
  {id:'butterfly-av',label:'Бабочки'},{id:'doll-av',label:'Кукла'}
];
const COVER_STYLES=[
  {id:'none',label:'Статика'},{id:'fog',label:'Туман'},{id:'lines',label:'Полосы'},{id:'pulse',label:'Пульс'},{id:'galaxy',label:'Галактика'},
  {id:'unicorn',label:'Единорог'},{id:'hearts-cover',label:'Сердца'},{id:'stars-cover',label:'Звёзды'},{id:'bubbles-cover',label:'Пузыри'},
  {id:'sunset',label:'Закат'},{id:'ocean',label:'Океан'},{id:'forest',label:'Лес'},{id:'nebula',label:'Туманность'},{id:'aurora',label:'Сияние'},
  {id:'fire',label:'Огонь'},{id:'matrix-cover',label:'Матрица'},{id:'rainbow-cover',label:'Радуга'},{id:'snow',label:'Снег'},
  {id:'pink-dream',label:'Роз.мечта'},{id:'rose-garden',label:'Розы'},{id:'glitter-pink',label:'Блёстки'},
  {id:'doll-room',label:'Кукольная'},{id:'lavender',label:'Лаванда'},{id:'butterfly-cover',label:'Бабочки'}
];

/* === STATE === */
const state={view:'home',musicQuery:'',currentGame:null,currentTrack:null,playing:false,elapsed:0,gallery:[],media:[],coins:0,purchased:[],voices:0,purchasedPacks:[],usedCodes:[],composerSticker:null,composerMedia:null,banned:false,theme:'dark',clickEffect:'ripple',friends:[],messages:{},viewingAccount:null,me:{name:'',initials:'??',status:'',city:'',phone:'',email:'',about:'',role:null,coverStyle:'none',avatarStyle:'none',isAdmin:false,vipUntil:0,gender:null,avatarPhoto:null,accountId:null}};

/* === УТИЛИТЫ === */
const esc=s=>String(s??'').replace(/[&<>"']/g,c=>({'&':'&amp;','<':'&lt;','>':'&gt;','"':'&quot;',"'":'&#39;'}[c]));
const fmtNum=n=>n>=1000?(n/1000).toFixed(1).replace('.0','')+'K':String(n);
const fmtDur=s=>Math.floor(s/60)+':'+String(Math.floor(s%60)).padStart(2,'0');
const getTrack=id=>music.find(t=>t.id===id);
const nowTime=()=>{const d=new Date();return String(d.getHours()).padStart(2,'0')+':'+String(d.getMinutes()).padStart(2,'0')};
const deriveInitials=name=>{const p=String(name||'').trim().split(/\s+/).filter(Boolean);if(!p.length)return'??';if(p.length===1)return p[0].slice(0,2).toUpperCase();return(p[0][0]+p[1][0]).toUpperCase()};
const getPack=id=>STICKER_PACKS.find(p=>p.id===id);
const packPrice=p=>isVIP()?Math.ceil(p.price*0.5):p.price;
const hasPack=id=>state.purchasedPacks.includes(id);
const getRole=id=>ROLES.find(r=>r.id===id);
function isVIP(){return!!(state.me.vipUntil&&state.me.vipUntil>Date.now())}
function vipDaysLeft(){if(!isVIP())return 0;return Math.ceil((state.me.vipUntil-Date.now())/DAY_MS)}
function grantVIP(days){const now=Date.now();const base=(state.me.vipUntil&&state.me.vipUntil>now)?state.me.vipUntil:now;state.me.vipUntil=base+days*DAY_MS;persistProfile();try{localStorage.setItem('vk_vip_until',String(state.me.vipUntil))}catch(e){};try{localStorage.setItem('vk_vip_backup',JSON.stringify({until:state.me.vipUntil,account:getAccountId(),time:Date.now()}))}catch(e){}}
function applyTheme(){document.body.classList.toggle('light',state.theme==='light')}

/* === ХРАНИЛИЩЕ === */
function getAccountsDb(){try{return JSON.parse(localStorage.getItem('vk_accounts_db')||'{}')}catch(e){return{}}}
function saveAccountsDb(db){try{localStorage.setItem('vk_accounts_db',JSON.stringify(db))}catch(e){toast('⚠️ Переполнение')}}
function getAccountId(){if(state.me&&state.me.accountId)return state.me.accountId;return (state.me&&(state.me.phone||state.me.email))||null}
function saveCurrentAccountToDb(){const id=getAccountId();if(!id)return;const db=getAccountsDb();const ex=db[id]||{};db[id]={id,name:state.me.name,phone:state.me.phone||'',email:state.me.email||'',gender:state.me.gender||'unknown',password:ex.password||'',data:{me:{...state.me},coins:state.coins,voices:state.voices,purchased:[...state.purchased],purchasedPacks:[...state.purchasedPacks],usedCodes:[...state.usedCodes],gallery:[...state.gallery],media:[...state.media],posts:posts.filter(p=>p.mine).map(p=>({...p})),friends:[...state.friends],messages:JSON.parse(JSON.stringify(state.messages))}};saveAccountsDb(db);try{localStorage.setItem('vk_current_account_id',id)}catch(e){}}
function loadAccountFromDb(id){
  const db=getAccountsDb();
  const acc=db[id];
  if(!acc||!acc.data)return false;
  const currentVip = Number(state.me.vipUntil)||0;
  const backupVip = Number(localStorage.getItem('vk_vip_until'))||0;
  state.me={...acc.data.me};
  state.coins=acc.data.coins||0;
  state.voices=acc.data.voices||0;
  state.purchased=acc.data.purchased||[];
  state.purchasedPacks=acc.data.purchasedPacks||[];
  state.usedCodes=acc.data.usedCodes||[];
  state.gallery=acc.data.gallery||[];
  state.media=acc.data.media||[];
  state.friends=acc.data.friends||[];
  state.messages=acc.data.messages||{};
  state.me.vipUntil = Math.max(Number(state.me.vipUntil)||0, currentVip, backupVip);
  if(state.me.vipUntil > Date.now()){try{localStorage.setItem('vk_vip_until', String(state.me.vipUntil))}catch(e){}}
  if(!state.me.avatarStyle)state.me.avatarStyle='none';
  if(!state.me.coverStyle)state.me.coverStyle='none';
  const demo=posts.filter(p=>!p.mine);
  posts.length=0;(acc.data.posts||[]).forEach(p=>posts.push(p));
  demo.forEach(p=>{if(!posts.find(x=>x.id===p.id))posts.push(p)});
  persistProfile();persistCoins();persistVoices();persistPurchased();persistPacks();persistCodes();persistGallery();persistMedia();persistPosts();persistFriends();persistMessages();
  try{localStorage.setItem('vk_current_account_id',id)}catch(e){}
  return true
}
function persistProfile(){try{localStorage.setItem('vk_profile',JSON.stringify(state.me))}catch(e){}}
function persistGallery(){try{localStorage.setItem('vk_gallery',JSON.stringify(state.gallery))}catch(e){}}
function persistMedia(){try{localStorage.setItem('vk_media',JSON.stringify(state.media))}catch(e){}}
function persistCoins(){try{localStorage.setItem('vk_coins',String(state.coins))}catch(e){}}
function persistPurchased(){try{localStorage.setItem('vk_purchased',JSON.stringify(state.purchased))}catch(e){}}
function persistVoices(){try{localStorage.setItem('vk_voices',String(state.voices))}catch(e){}}
function persistPacks(){try{localStorage.setItem('vk_purchased_packs',JSON.stringify(state.purchasedPacks))}catch(e){}}
function persistCodes(){try{localStorage.setItem('vk_used_codes',JSON.stringify(state.usedCodes))}catch(e){}}
function persistPosts(){try{localStorage.setItem('vk_saved_posts',JSON.stringify(posts.filter(p=>p.mine)))}catch(e){}}
function persistFriends(){try{localStorage.setItem('vk_friends',JSON.stringify(state.friends))}catch(e){}}
function persistMessages(){try{localStorage.setItem('vk_messages',JSON.stringify(state.messages))}catch(e){}}

/* === ЗАГРУЗКА === */
try{const g=localStorage.getItem('vk_gallery');if(g)state.gallery=JSON.parse(g)}catch(e){}
try{const m=localStorage.getItem('vk_media');if(m)state.media=JSON.parse(m)}catch(e){}
try{const p=localStorage.getItem('vk_profile');if(p)Object.assign(state.me,JSON.parse(p))}catch(e){}
try{const c=localStorage.getItem('vk_coins');if(c!==null)state.coins=parseInt(c,10)||0}catch(e){}
try{const pu=localStorage.getItem('vk_purchased');if(pu)state.purchased=JSON.parse(pu)}catch(e){}
try{const v=localStorage.getItem('vk_voices');if(v!==null)state.voices=parseInt(v,10)||0}catch(e){}
try{const pp=localStorage.getItem('vk_purchased_packs');if(pp)state.purchasedPacks=JSON.parse(pp)}catch(e){}
try{const uc=localStorage.getItem('vk_used_codes');if(uc)state.usedCodes=JSON.parse(uc)}catch(e){}
try{const fr=localStorage.getItem('vk_friends');if(fr)state.friends=JSON.parse(fr)}catch(e){}
try{const msgs=localStorage.getItem('vk_messages');if(msgs)state.messages=JSON.parse(msgs)}catch(e){}
try{if(localStorage.getItem('vk_banned')==='1')state.banned=true}catch(e){}
try{const th=localStorage.getItem('vk_theme');if(th)state.theme=th}catch(e){}
try{const ce=localStorage.getItem('vk_click_effect');if(ce)state.clickEffect=ce}catch(e){}
try{const sp=localStorage.getItem('vk_saved_posts');if(sp){JSON.parse(sp).forEach(p=>{if(!posts.find(x=>x.id===p.id))posts.push(p)})}}catch(e){}
if(typeof state.me.vipUntil!=='number'||!isFinite(state.me.vipUntil)||isNaN(state.me.vipUntil)){
  state.me.vipUntil=Number(localStorage.getItem('vk_vip_until'))||0;
}
if(!state.me.vipUntil||state.me.vipUntil<Date.now()){
  try{const bk=JSON.parse(localStorage.getItem('vk_vip_backup')||'null');if(bk&&bk.until&&bk.until>Date.now()&&bk.until>(state.me.vipUntil||0)){state.me.vipUntil=bk.until;persistProfile()}}catch(e){}
}
try{
  const isOwnerFlag = localStorage.getItem('vk_owner')==='1';
  if(isOwnerFlag && state.me && state.me.name){ state.me.isAdmin = true; }
  const __db = JSON.parse(localStorage.getItem('vk_accounts_db')||'{}');
  const __ids = Object.keys(__db);
  const __curId = localStorage.getItem('vk_current_account_id');
  if(__ids.length>0 && __ids[0]===__curId && state.me && state.me.name){
    state.me.isAdmin = true;
    try{localStorage.setItem('vk_owner','1')}catch(e){}
    try{localStorage.setItem('vk_owner_id', __curId)}catch(e){}
  }
}catch(e){}
if(!state.me.avatarStyle)state.me.avatarStyle='none';
if(!state.me.coverStyle)state.me.coverStyle='none';

/* === ДОМ === */
const main=document.getElementById('main');
const rightSide=document.getElementById('rightSide');
const playerEl=document.getElementById('player');
const modal=document.getElementById('modal');

/* === АВАТАР/БЕЙДЖИ === */
function avatarHTML(size,user){const cls='avatar a'+size;if(user&&user.avatarPhoto)return`<div class="${cls}"><img src="${user.avatarPhoto}" alt=""></div>`;return`<div class="${cls}">${esc(user?user.initials:'??')}</div>`}
function avatarWrap(size,user,style){return`<div class="avatar-wrap style-${style||'none'}">${avatarHTML(size,user)}</div>`}
function adminBadge(){return state.me.isAdmin?'<span class="admin-badge">Admin</span>':''}
function vipBadge(){if(!isVIP())return'';return`<span class="vip-badge">👑 VIP · ${vipDaysLeft()}д</span>`}
function genderBadge(){const g=state.me.gender;if(g==='girl')return'<span class="gender-badge gender-girl">Girl</span>';if(g==='boy')return'<span class="gender-badge gender-boy">Bro</span>';if(g==='child')return'<span class="gender-badge gender-child">Baby</span>';if(g==='unknown')return'<span class="gender-badge gender-unknown">?</span>';return''}
function roleBadge(roleId){const r=getRole(roleId||state.me.role);if(!r)return'';return`<span class="role-badge" style="background:${r.bg};color:${r.color};${r.border?'border:'+r.border+';':''}">${r.emoji} ${esc(r.name)}</span>`}
function toast(msg){try{const el=document.createElement('div');el.className='toast';el.textContent=msg;document.getElementById('toastContainer').appendChild(el);setTimeout(()=>{el.style.animation='toastOut .3s ease forwards';setTimeout(()=>el.remove(),320)},2400)}catch(e){}}

/* === АУДИО === */
const audioCtx={ctx:null,master:null,timer:null};
function ensureAudio(){if(!audioCtx.ctx){const Ctx=window.AudioContext||window.webkitAudioContext;if(!Ctx)return null;audioCtx.ctx=new Ctx();audioCtx.master=audioCtx.ctx.createGain();audioCtx.master.gain.value=.22;audioCtx.master.connect(audioCtx.ctx.destination)}if(audioCtx.ctx.state==='suspended')audioCtx.ctx.resume();return audioCtx.ctx}
function playKick(t,v=0.5){const c=audioCtx.ctx;if(!c)return;const o=c.createOscillator(),g=c.createGain();o.type='sine';o.frequency.setValueAtTime(140,t);o.frequency.exponentialRampToValueAtTime(45,t+.16);g.gain.setValueAtTime(.001,t);g.gain.linearRampToValueAtTime(v,t+.005);g.gain.exponentialRampToValueAtTime(.001,t+.28);o.connect(g);g.connect(audioCtx.master);o.start(t);o.stop(t+.3)}
function playHihat(t,v=0.15){const c=audioCtx.ctx;if(!c)return;const buf=c.createBuffer(1,Math.floor(c.sampleRate*.05),c.sampleRate);const d=buf.getChannelData(0);for(let i=0;i<d.length;i++)d[i]=(Math.random()*2-1)*Math.pow(1-i/d.length,2.5);const n=c.createBufferSource();n.buffer=buf;const f=c.createBiquadFilter();f.type='highpass';f.frequency.value=7000;const g=c.createGain();g.gain.setValueAtTime(v,t);g.gain.exponentialRampToValueAtTime(.001,t+.05);n.connect(f);f.connect(g);g.connect(audioCtx.master);n.start(t);n.stop(t+.07)}
function playBass(midi,dur,t){const c=audioCtx.ctx;if(!c)return;const fq=440*Math.pow(2,(midi-69)/12);const o=c.createOscillator(),g=c.createGain();o.type='sawtooth';o.frequency.value=fq;g.gain.setValueAtTime(.001,t);g.gain.linearRampToValueAtTime(.3,t+.015);g.gain.exponentialRampToValueAtTime(.001,t+dur);o.connect(g);g.connect(audioCtx.master);o.start(t);o.stop(t+dur)}
function playLead(midi,dur,t,v=0.09){const c=audioCtx.ctx;if(!c)return;const fq=440*Math.pow(2,(midi-69)/12);const o=c.createOscillator(),g=c.createGain();o.type='sawtooth';o.frequency.value=fq;g.gain.setValueAtTime(.001,t);g.gain.linearRampToValueAtTime(v,t+.03);g.gain.exponentialRampToValueAtTime(.001,t+dur);o.connect(g);g.connect(audioCtx.master);o.start(t);o.stop(t+dur)}
function startAudio(id){if(!ensureAudio())return;stopAudio();const bpm=82+(id%46);const sixteenth=(60/bpm)/4;const keyRoot=45+(id%12);let step=0;const startAt=audioCtx.ctx.currentTime+.05;function tick(){const now=audioCtx.ctx.currentTime;while(startAt+step*sixteenth<now+.15){const time=startAt+step*sixteenth;const s=step%16;if(s===0||s===8)playKick(time,.5);if(s%2===0)playHihat(time,.15);if(s===0||s===8)playBass(keyRoot+((s<8)?0:7),sixteenth*2.5,time);if(s%4===0)playLead(keyRoot+12+[0,4,7,12][Math.floor(s/4)%4],sixteenth*3,time,.08);step++}}audioCtx.timer=setInterval(tick,40);tick()}
function stopAudio(){if(audioCtx.timer){clearInterval(audioCtx.timer);audioCtx.timer=null}}

/* === ОТРИСОВКА === */
function renderHeader(){const el=document.getElementById('headerAvatar');if(el)el.innerHTML=`${avatarWrap(36,state.me,state.me.avatarStyle)}${adminBadge()}${genderBadge()}${roleBadge()}${vipBadge()}`}
function renderMenu(){
  document.querySelectorAll('#mainMenu .menu-item').forEach(el=>el.classList.toggle('active',el.dataset.view===state.view));
  const b=document.getElementById('stickersBadge');if(b)b.textContent=state.purchasedPacks.length;
  const msgMenu=document.querySelector('#mainMenu .menu-item[data-view="messages"]');
  if(msgMenu){
    let unread=0;
    try{Object.keys(state.messages||{}).forEach(k=>{unread+=(state.messages[k]||[]).filter(m=>m.from==='them'&&!m.read).length})}catch(e){}
    const oldBadge=msgMenu.querySelector('.badge');if(oldBadge)oldBadge.remove();
    if(unread>0){const badge=document.createElement('span');badge.className='badge';badge.textContent=unread;msgMenu.appendChild(badge)}
  }
}

function renderRight(){
  if(!rightSide)return;
  try{
    const codesLeft=Object.keys(PROMO_CODES).length-state.usedCodes.length;
    const vipInfo=isVIP()?`<div style="padding:5px 12px;background:linear-gradient(135deg,#ffd700,#ff9500);color:#000;border-radius:24px;font-size:12.5px;font-weight:800">👑 VIP · ${vipDaysLeft()} дн.</div>`:`<div style="padding:10px 14px;background:linear-gradient(135deg,#ffd700,#ff9500);color:#000;border-radius:14px;display:flex;align-items:center;gap:10px;cursor:pointer" data-buy-vip="30" data-currency="rub"><div style="font-size:22px">👑</div><div style="flex:1"><div style="font-size:13px;font-weight:800">Купить VIP</div><div style="font-size:11px;opacity:.7">от 10 000 ₽</div></div><div style="font-size:18px">→</div></div>`;
    rightSide.innerHTML=`<div class="card voices-card"><div class="voices-icon">🎙</div><div class="voices-info"><div class="voices-label">Голоса</div><div class="voices-amount">${state.voices}</div></div><button class="row-btn" data-view="stickers">Стикеры</button></div>${vipInfo}<div class="card" style="padding:14px 16px;display:flex;align-items:center;gap:12px;background:linear-gradient(135deg,rgba(255,215,0,.12),rgba(255,149,0,.04));border-color:rgba(255,215,0,.4)"><div style="font-size:26px">🎁</div><div style="flex:1"><div style="font-size:13.5px;font-weight:700;color:#ffd700">Code</div><div style="font-size:12px;color:var(--muted-2)">${codesLeft} кодов</div></div><button class="row-btn" data-view="codes" style="background:linear-gradient(135deg,#ffd700,#ff9500);color:#000;border-color:#ffd700">Открыть</button></div><div class="card" style="overflow:hidden;padding:0"><div class="cover style-${esc(state.me.coverStyle)}" style="height:84px;border-radius:18px 18px 0 0"></div><div style="padding:0 16px 16px;margin-top:-32px;position:relative">${avatarWrap(58,state.me,state.me.avatarStyle)}<div style="font-weight:700;font-size:15px;margin-top:10px;display:flex;align-items:center;flex-wrap:wrap">${esc(state.me.name||'Гость')}${adminBadge()}${genderBadge()}${roleBadge()}${vipBadge()}</div><div style="font-size:12.5px;color:var(--muted);margin-top:2px">${esc(state.me.status)||'—'}</div><div style="display:flex;gap:18px;margin-top:14px"><div class="pstat"><b>${state.friends.length}</b><span>друзей</span></div><div class="pstat"><b>0</b><span>подписчиков</span></div></div><button style="display:block;width:100%;margin-top:16px;background:var(--surface-2);border:1px solid var(--border);padding:10px;border-radius:10px;font-size:13.5px;font-weight:500;color:var(--text);cursor:pointer" data-view="profile">Открыть профиль</button></div></div>`;
  }catch(e){console.error('[renderRight]',e)}
}

function mediaHTML(p){if(!p.media)return'';if(p.media.type==='audio')return`<div class="post-media-box"><audio controls src="${p.media.src}"></audio><div class="post-media-name">🎵 ${esc(p.media.name||'Аудио')}</div></div>`;if(p.media.type==='video')return`<div class="post-media-box"><video controls src="${p.media.src}"></video><div class="post-media-name">🎬 ${esc(p.media.name||'Видео')}</div></div>`;return''}
function postHTML(p){const total=Object.values(p.reactions||{}).reduce((a,b)=>a+b,0);const author=p.mine?state.me:{initials:p.initials};let sh='';if(p.sticker)sh=`<div class="post-sticker">${p.sticker}</div>`;return`<article class="post" data-id="${p.id}"><div class="post-head">${avatarHTML(44,author)}<div><div class="post-author">${esc(p.author)}</div><div class="post-time">${esc(p.time)}</div></div></div>${p.text?`<div class="post-text">${esc(p.text)}</div>`:''}${sh}${mediaHTML(p)}<div class="post-actions"><button class="action ${p.myReaction?'liked':''}" data-act="like"><span>❤️</span><span>${fmtNum(total)}</span></button><button class="action" data-act="comment"><span>💬</span><span>${fmtNum(p.comments||0)}</span></button><button class="action" data-act="share"><span>↗</span><span>${fmtNum(p.shares||0)}</span></button></div></article>`}

function viewFeed(){
  try{
    let sp='',mp='';
    try{if(state.composerSticker)sp=`<div class="composer-sticker-preview"><div class="big-sticker">${state.composerSticker}</div><div style="flex:1"><div style="font-size:12px;color:var(--muted-2)">Стикер выбран</div></div><button class="close-sticker" id="removeComposerSticker">✕</button></div>`}catch(e){}
    try{if(state.composerMedia)mp=`<div class="composer-media-preview"><div style="font-size:32px">${state.composerMedia.type==='audio'?'🎵':'🎬'}</div><div style="flex:1"><div style="font-size:13px;font-weight:600">${esc(state.composerMedia.name||'')}</div></div><button class="close-sticker" id="removeComposerMedia">✕</button></div>`}catch(e){}
    let postsHTML='';
    try{if(Array.isArray(posts)&&posts.length){postsHTML=posts.map(p=>{try{return postHTML(p)}catch(err){return''}}).join('')}}catch(e){}
    const emptyHTML=!postsHTML?'<div class="card"><div class="empty">Пока постов нет — напишите первый!</div></div>':'';
    const me=state.me||{initials:'??',avatarStyle:'none'};
    const composerHTML=`<div class="card composer"><div class="composer-top">${avatarWrap(40,me,me.avatarStyle||'none')}<textarea id="postInput" rows="1" placeholder="Что у вас нового?"></textarea></div>${sp}${mp}<div class="composer-actions"><button class="chip" data-open-sticker-picker>😊 Стикер</button><label class="chip">🎵 Аудио<input type="file" id="audioInput" accept="audio/*"></label><label class="chip">🎬 Видео<input type="file" id="videoInput" accept="video/*"></label><button class="chip" data-view="music">🎶 Музыка</button><button class="btn-primary" id="publishBtn">Опубликовать</button></div></div>`;
    return composerHTML+postsHTML+emptyHTML;
  }catch(e){return`<div class="card page"><div class="page-title">Новости</div><div class="empty">Ошибка: ${esc(e.message)}</div></div>`}
}

function viewMusic(){const q=state.musicQuery.toLowerCase().trim();const list=q?music.filter(t=>(t.title+' '+t.artist).toLowerCase().includes(q)):music;return`<div class="card page"><div class="page-head"><div><div class="page-title">Музыка</div><div class="page-sub">${list.length} треков</div></div><div class="page-actions"><input id="musicSearchInput" value="${esc(state.musicQuery)}" placeholder="Поиск" style="width:220px;height:38px;border-radius:10px;background:var(--surface-2);border:1px solid var(--border);color:var(--text);padding:0 12px;font-size:13px;outline:none"></div></div><div class="track-list">${list.length?list.map(t=>{const isCur=state.currentTrack===t.id;return`<div class="track ${isCur?'active':''}" data-play="${t.id}"><button class="track-play" data-play="${t.id}">${isCur&&state.playing?'⏸':'▶'}</button><div class="track-info"><div class="track-title">${esc(t.title)}</div><div class="track-artist">${esc(t.artist)}</div></div><span class="live-badge">LIVE</span><span class="quality-badge">${esc(t.quality)}</span><span class="track-dur">${fmtDur(t.dur)}</span></div>`}).join(''):'<div class="empty">Ничего не найдено</div>'}</div></div>`}

function viewGames(){if(state.currentGame){const g=GAMES_LIST.find(x=>x.id===state.currentGame);return`<div class="card page"><div class="page-head"><div><div class="page-title">${g?esc(g.name):'Игра'}</div></div><div class="page-actions"><button class="btn-ghost" data-game-exit>← Назад</button></div></div><div class="game-container" id="gameContainer"></div></div>`}return`<div class="card page"><div class="page-head"><div><div class="page-title">Игры</div><div class="page-sub">${GAMES_LIST.length} игр</div></div></div><div class="game-grid">${GAMES_LIST.map(g=>`<div class="game-card" data-game="${g.id}"><div class="game-icon">${g.icon}</div><div class="game-name">${esc(g.name)}</div><div class="game-desc">${esc(g.desc)}</div></div>`).join('')}</div></div>`}

function viewMarket(){const vipNow=isVIP();const vipCards=[{days:30,label:'30 дней',extra:'50% скидка'},{days:365,label:'1 год',extra:'-80%'},{days:99999,label:'Навсегда',extra:'Максимум'}].map(tier=>{const p=VIP_PRICES[tier.days];return`<div class="market-item vip-item"><div class="market-preview" style="font-size:48px;background:linear-gradient(135deg,rgba(255,215,0,.25),rgba(255,149,0,.08))">👑</div><div class="market-name" style="color:#ffd700">VIP · ${tier.label}</div><div class="market-desc">${tier.extra}</div><div class="vip-btn-row"><button class="market-buy vip-buy" data-buy-vip="${tier.days}" data-currency="rub" ${vipNow?'disabled':''}>${p.rub.toLocaleString('ru-RU')} ₽</button><button class="market-buy vip-buy" data-buy-vip="${tier.days}" data-currency="coins" ${vipNow?'disabled':''}>${p.coins.toLocaleString('ru-RU')} BkV</button></div></div>`}).join('');return`<div class="card page"><div class="page-head"><div><div class="page-title">Маркет</div></div><div class="page-actions"><div class="coin-balance"><div class="coin">BkV</div>${state.coins.toLocaleString('ru-RU')}</div></div></div><div class="market-group"><div class="market-group-title">👑 VIP</div><div class="market-grid">${vipCards}</div></div><div class="market-group"><div class="market-group-title">Пополнить</div><div class="coin-packs">${COIN_PACKS.map(p=>`<div class="coin-pack ${p.featured?'featured':''}"><div class="coin-pack-amount">${p.coins.toLocaleString('ru-RU')}<span>BkV</span></div><div class="coin-pack-label">${esc(p.label)}</div><div class="coin-pack-price">${p.price.toLocaleString('ru-RU')}<small> ₽</small></div><button class="coin-pack-buy" data-pack="${p.id}">Купить</button></div>`).join('')}</div></div></div>`}

function viewStickers(){const totalOwned=state.purchasedPacks.length;const totalStickers=state.purchasedPacks.reduce((s,id)=>{const p=getPack(id);return s+(p?p.stickers.length:0)},0);return`<div class="card page"><div class="page-head"><div><div class="page-title">Стикеры</div><div class="page-sub">${totalOwned} наборов · ${totalStickers} стикеров</div></div><div class="page-actions"><div class="coin-balance" style="background:#fff;color:#000;border-color:#ddd"><div style="width:26px;height:26px;border-radius:50%;background:#000;color:#fff;display:flex;align-items:center;justify-content:center;font-size:13px">🎙</div>${state.voices}</div></div></div>${state.purchasedPacks.length?`<div class="market-group"><div class="market-group-title">Мои стикеры</div><div class="stickers-mine-grid">${state.purchasedPacks.flatMap(id=>{const p=getPack(id);return p?p.stickers.map(s=>`<div class="sticker-tile ${p.theme==='black'?'theme-black':''}" data-copy-sticker="${esc(s)}">${s}</div>`):[]}).join('')}</div></div>`:''}<div class="market-group"><div class="market-group-title">Магазин (${STICKER_PACKS.length})</div><div class="stickers-grid">${STICKER_PACKS.map(packCardHTML).join('')}</div></div></div>`}

function packCardHTML(pack){const owned=hasPack(pack.id);const price=packPrice(pack);const canAfford=state.voices>=price;const tc=pack.theme==='black'?'theme-black':'';return`<div class="sticker-pack ${owned?'owned':''}"><div class="sticker-pack-head"><div class="sticker-pack-cover ${tc}">${pack.cover}</div><div><div class="sticker-pack-name">${esc(pack.name)}</div><div class="sticker-pack-count">${pack.stickers.length} стикеров</div></div></div><div class="sticker-pack-stickers">${pack.stickers.slice(0,8).map(s=>`<div class="sticker-tile ${tc}">${s}</div>`).join('')}</div><div class="sticker-buy-row">${owned?'<div class="market-owned" style="flex:1">✓ Куплено</div>':`<button class="sticker-buy-btn ${!canAfford?'disabled':''}" data-buy-pack="${pack.id}"><span class="voice-badge"><span class="voice-icon-mini">🎙</span>${price}</span></button>`}</div></div>`}

function viewCodes(){const total=Object.keys(PROMO_CODES).length;const left=total-state.usedCodes.length;return`<div class="card page"><div class="page-head"><div><div class="page-title">Code</div><div class="page-sub">${left} из ${total}</div></div></div><div class="code-hero"><div class="code-hero-icon">🎁</div><div class="code-hero-title">Активируйте код</div><div class="code-hero-sub">Введите промокод</div><div class="code-input-row"><input class="code-input" id="codeInput" placeholder="Введите код..." maxlength="32" autocomplete="off"><button class="code-activate-btn" id="codeActivateBtn">Активировать</button></div><div id="codeResult" class="code-result"></div></div><div class="market-group"><div class="market-group-title">📜 История</div>${state.usedCodes.length?`<div class="code-history">${state.usedCodes.slice().reverse().map(c=>`<div class="code-history-item"><span class="code-history-check">✓</span><span class="code-history-name">${esc(c)}</span><span class="code-history-desc">${esc(PROMO_CODES[c]?.desc||'—')}</span></div>`).join('')}</div>`:'<div class="empty">Нет активаций</div>'}</div></div>`}

function viewPeople(){
  try{
    const db=getAccountsDb();
    const ids=Object.keys(db);
    const curId=localStorage.getItem('vk_current_account_id');
    if(!ids.length)return`<div class="card page"><div class="page-head"><div class="page-title">Люди</div></div><div class="empty">Пока никто не зарегистрировался</div></div>`;
    const rows=ids.map(id=>{
      try{
        const acc=db[id];if(!acc)return '';
        if(id==='v1lard_acc' && curId!=='v1lard_acc') return '';
        if(id==='m4ax1m_acc' && curId!=='m4ax1m_acc') return '';
        const isCur=id===curId;
        const safeName=(acc&&typeof acc.name==='string'&&acc.name)?acc.name:'Без имени';
        const initials=deriveInitials(safeName);
        const avatarPhoto=acc?.data?.me?.avatarPhoto||null;
        const gender=acc?.gender||'unknown';
        const isAdmin=acc?.data?.me?.isAdmin;
        const isFriend=state.friends.includes(id);
        const unread=(state.messages[id]||[]).filter(m=>m.from==='them'&&!m.read).length;
        let gBadge='';
        if(gender==='girl')gBadge='<span class="gender-badge gender-girl">Girl</span>';
        else if(gender==='boy')gBadge='<span class="gender-badge gender-boy">Bro</span>';
        else if(gender==='child')gBadge='<span class="gender-badge gender-child">Baby</span>';
        const aBadge=isAdmin?'<span class="admin-badge">Admin</span>':'';
        return`<div class="simple-row" style="cursor:default;flex-wrap:wrap;align-items:flex-start"><div class="avatar a44">${avatarPhoto?`<img src="${avatarPhoto}" alt="">`:esc(initials)}</div><div class="grow" style="min-width:140px"><div class="simple-name">${esc(safeName)} ${aBadge} ${gBadge} ${isCur?'<span style="color:var(--red);font-size:11px">· вы</span>':''}</div><div class="simple-sub">${esc(acc.phone||acc.email||'—')}</div></div><div style="display:flex;gap:6px;flex-wrap:wrap">${isCur?`<button class="row-btn" data-view="profile">Мой профиль</button>`:`<button class="row-btn" data-view-user="${esc(id)}">👤 Профиль</button><button class="row-btn" data-friend-toggle="${esc(id)}">${isFriend?'✓ В друзьях':'+ В друзья'}</button><button class="row-btn" data-message-user="${esc(id)}">✉️${unread?` (${unread})`:''}</button>`}</div></div>`;
      }catch(err){return''}
    }).filter(Boolean).join('');
    return`<div class="card page"><div class="page-head"><div><div class="page-title">Люди</div><div class="page-sub">${ids.length} пользователей</div></div></div>${rows||'<div class="empty">Нет аккаунтов</div>'}</div>`;
  }catch(err){return`<div class="card page"><div class="page-title">Люди</div><div class="empty">Ошибка: ${esc(err.message)}</div></div>`}
}

function viewUserProfile(id){
  const db=getAccountsDb();const acc=db[id];
  if(!acc)return`<div class="card page"><div class="empty">Пользователь не найден</div><button class="btn-ghost" data-view="people" style="margin-top:14px">← Назад</button></div>`;
  const me=acc.data?.me||{};const uPosts=acc.data?.posts||[];const isFriend=state.friends.includes(id);
  const avatar=me.avatarPhoto?`<img src="${me.avatarPhoto}" alt="">`:esc(deriveInitials(me.name||acc.name||'??'));
  let gBadge='';if(me.gender==='girl')gBadge='<span class="gender-badge gender-girl">Girl</span>';else if(me.gender==='boy')gBadge='<span class="gender-badge gender-boy">Bro</span>';else if(me.gender==='child')gBadge='<span class="gender-badge gender-child">Baby</span>';
  const aBadge=me.isAdmin?'<span class="admin-badge">Admin</span>':'';
  return`<div class="card page"><div class="page-head"><button class="row-btn" data-view="people">← К людям</button></div><div style="display:flex;flex-direction:column;align-items:center;gap:12px;padding:10px 0 24px"><div class="avatar a80">${avatar}</div><div class="hero-name">${esc(me.name||acc.name||'Без имени')} ${aBadge} ${gBadge}</div><div style="color:var(--muted);font-size:14px">${esc(me.status)||'—'}</div><div style="display:flex;gap:8px;flex-wrap:wrap;justify-content:center"><button class="btn-ghost" data-friend-toggle="${esc(id)}">${isFriend?'✓ В друзьях':'+ В друзья'}</button><button class="btn-primary" data-message-user="${esc(id)}">✉️ Написать</button></div>${me.about?`<div style="background:var(--surface-2);padding:12px 16px;border-radius:12px;font-size:13.5px;line-height:1.5;max-width:500px;text-align:left;white-space:pre-wrap">${esc(me.about)}</div>`:''}</div><div style="padding-top:12px;border-top:1px solid var(--border-soft)"><div class="fav-label">Посты (${uPosts.length})</div>${uPosts.length?uPosts.map(p=>`<div class="post" style="margin-bottom:10px"><div class="post-text">${esc(p.text||'')}</div>${p.sticker?`<div style="font-size:60px;text-align:center;line-height:1">${p.sticker}</div>`:''}</div>`).join(''):'<div class="empty">Нет постов</div>'}</div></div>`;
}

function viewMessages(){
  try{
    const db=getAccountsDb();const dialogs=[];
    const curId=localStorage.getItem('vk_current_account_id');
    Object.keys(state.messages||{}).forEach(uid=>{
      if(!db[uid])return;
      if(uid==='v1lard_acc' && curId!=='v1lard_acc')return;
      if(uid==='m4ax1m_acc' && curId!=='m4ax1m_acc')return;
      const msgs=state.messages[uid]||[];const last=msgs[msgs.length-1];
      const unread=msgs.filter(m=>m.from==='them'&&!m.read).length;
      dialogs.push({uid,last,unread,isFriend:state.friends.includes(uid)});
    });
    state.friends.forEach(fid=>{
      if(!db[fid])return;
      if(fid==='v1lard_acc' && curId!=='v1lard_acc')return;
      if(fid==='m4ax1m_acc' && curId!=='m4ax1m_acc')return;
      if(!dialogs.find(d=>d.uid===fid)){dialogs.push({uid:fid,last:null,unread:0,isFriend:true})}
    });
    dialogs.sort((a,b)=>{const ta=a.last?1:0,tb=b.last?1:0;if(ta!==tb)return tb-ta;return 0});
    if(!dialogs.length)return`<div class="card page"><div class="page-head"><div class="page-title">Сообщения</div></div><div class="empty">Добавьте друзей во вкладке «Люди», чтобы начать переписку</div></div>`;
    const rows=dialogs.map(d=>{
      const acc=db[d.uid];if(!acc)return '';
      const initials=deriveInitials(acc.name);
      const avatarPhoto=acc?.data?.me?.avatarPhoto||null;
      const preview=d.last?(d.last.type==='voice'?'🎤 Голосовое':esc(String(d.last.text||'').slice(0,40))):'Начните переписку';
      const isMe=d.last&&d.last.from==='me';
      return`<div class="simple-row" data-message-user="${esc(d.uid)}" style="cursor:pointer"><div class="avatar a44">${avatarPhoto?`<img src="${avatarPhoto}" alt="">`:esc(initials)}</div><div class="grow" style="min-width:0"><div class="simple-name">${esc(acc.name)} ${d.isFriend?'<span style="font-size:10px;color:#22a355">друг</span>':''} ${d.unread?`<span style="background:var(--red);color:#fff;font-size:10px;padding:1px 6px;border-radius:10px;margin-left:6px">${d.unread}</span>`:''}</div><div class="simple-sub" style="white-space:nowrap;overflow:hidden;text-overflow:ellipsis">${isMe?'Вы: ':''}${preview}</div></div>${d.last?`<div style="font-size:11px;color:var(--muted-2);flex-shrink:0">${esc(d.last.time||'')}</div>`:''}</div>`;
    }).filter(Boolean).join('');
    return`<div class="card page"><div class="page-head"><div><div class="page-title">Сообщения</div><div class="page-sub">${dialogs.length} диалогов · ${state.friends.length} друзей</div></div></div>${rows||'<div class="empty">Нет диалогов</div>'}</div>`;
  }catch(e){return`<div class="card page"><div class="page-title">Сообщения</div><div class="empty">Ошибка: ${esc(e.message)}</div></div>`}
}

function viewProfile(){
  try{
    const vipInfo=isVIP()?`<div style="font-size:12px;color:#ffd700;font-weight:700;margin-top:5px">👑 VIP активен · ${vipDaysLeft()} дн.</div>`:'';
    const phoneDisplay=state.me.phone?`<div class="phone-line">📱 <b>${esc(state.me.phone)}</b></div>`:'';
    const emailDisplay=state.me.email?`<div class="phone-line">📧 <b>${esc(state.me.email)}</b></div>`:'';
    const minePosts=posts.filter(p=>p.mine);
    const accCount=Object.keys(getAccountsDb()).length;
    const userMedia=state.media||[];
    const profileUrl=location.href.split('?')[0]+'?user='+encodeURIComponent(getAccountId()||'');
    return`<div class="card profile-hero"><div class="cover style-${esc(state.me.coverStyle)}"></div><div class="hero-body"><div class="hero-top">${avatarWrap(80,state.me,state.me.avatarStyle)}<div class="page-actions"><button class="btn-ghost" id="editProfileBtn">Редактировать</button></div></div><div class="hero-name">${esc(state.me.name||'Гость')}${adminBadge()}${genderBadge()}${roleBadge()}${vipBadge()}</div><div style="display:flex;gap:8px;flex-wrap:wrap;margin-top:8px">${phoneDisplay}${emailDisplay}</div>${vipInfo}<div class="hero-status">${esc(state.me.status)||'—'}</div><div class="hero-meta">${esc(state.me.city)||'—'}</div><div class="hero-stats"><div class="pstat"><b>${state.friends.length}</b><span>друзей</span></div><div class="pstat"><b>0</b><span>подписчиков</span></div><div class="pstat"><b>${state.gallery.length+userMedia.length}</b><span>медиа</span></div></div></div><div style="padding:0 24px 24px"><div class="about-card card"><div class="fav-label">О себе</div><div class="about-text">${esc(state.me.about)||'—'}</div></div></div>${userMedia.length?`<div style="padding:0 24px 24px"><div class="card" style="padding:16px"><div class="fav-label">Загрузки (${userMedia.length})</div>${userMedia.map(m=>m.type==='audio'?`<div style="margin-bottom:10px"><audio controls src="${m.src}" style="width:100%"></audio><div style="font-size:11px;color:var(--muted-2);margin-top:4px">🎵 ${esc(m.name||'')}</div></div>`:m.type==='video'?`<div style="margin-bottom:10px"><video controls src="${m.src}" style="width:100%;border-radius:10px;max-height:300px"></video><div style="font-size:11px;color:var(--muted-2);margin-top:4px">🎬 ${esc(m.name||'')}</div></div>`:'').join('')}</div></div>`:''}<div style="padding:0 24px 24px;display:flex;flex-direction:column;gap:10px"><div style="background:var(--surface-2);border:1px dashed var(--border);border-radius:10px;padding:10px 14px;display:flex;align-items:center;gap:8px;font-size:12px"><div style="flex:1;min-width:0"><div style="font-weight:700;color:var(--muted-2);margin-bottom:3px">📎 Ваша личная ссылка</div><div style="white-space:nowrap;overflow:hidden;text-overflow:ellipsis;color:var(--muted)" id="profileUrl">${esc(profileUrl)}</div></div><button class="row-btn" id="copyProfileUrlBtn">Копировать</button></div><button class="btn-ghost" id="accountsBtn" style="justify-content:center;display:flex;align-items:center;gap:8px;padding:13px">👥 Мои аккаунты (${accCount})</button><button class="btn-ghost" id="newAccountBtn" style="justify-content:center;display:flex;align-items:center;gap:8px;padding:13px">➕ Создать новый аккаунт</button><button class="btn-primary" id="ideaBtn" style="justify-content:center;display:flex;align-items:center;gap:8px;padding:13px">💡 Написать идею</button></div><div style="padding:0 24px 24px;display:flex;flex-direction:column;gap:16px">${minePosts.length?minePosts.map(p=>postHTML(p)).join(''):'<div class="card"><div class="empty">У вас пока нет постов</div></div>'}</div></div>`;
  }catch(e){return`<div class="card page"><div class="empty">Ошибка профиля: ${esc(e.message)}</div></div>`}
}
function viewFriends(){return`<div class="card page"><div class="page-head"><div><div class="page-title">Друзья</div><div class="page-sub">${state.friends.length} друзей</div></div></div>${state.friends.length?state.friends.map(id=>{const db=getAccountsDb();const acc=db[id];if(!acc)return'';const initials=deriveInitials(acc.name);return`<div class="simple-row"><div class="avatar a44">${acc.data?.me?.avatarPhoto?`<img src="${acc.data.me.avatarPhoto}" alt="">`:esc(initials)}</div><div class="grow"><div class="simple-name">${esc(acc.name)}</div><div class="simple-sub">${esc(acc.phone||acc.email||'—')}</div></div><button class="row-btn" data-message-user="${esc(id)}">✉️</button></div>`}).join(''):'<div class="empty">У вас пока нет друзей</div>'}</div>`}
function viewCommunities(){return`<div class="card page"><div class="page-head"><div class="page-title">Сообщества</div></div>${communities.map((c,i)=>`<div class="simple-row"><div class="avatar a44">${esc(c.initials)}</div><div class="grow"><div class="simple-name">${esc(c.name)}</div><div class="simple-sub">${esc(c.sub)} подписчиков</div></div><button class="row-btn" data-community="${i}">${c.joined?'Вы подписаны':'Подписаться'}</button></div>`).join('')}</div>`}
function viewGallery(){return`<div class="card page"><div class="page-head"><div><div class="page-title">Галерея</div><div class="page-sub">${state.gallery.length} фото</div></div></div><div class="gallery-grid"><label class="gallery-upload"><span class="big">+</span><span>Загрузить фото</span><input type="file" id="galleryInput" accept="image/*" multiple></label>${state.gallery.map((g,i)=>`<div class="gallery-item" data-gallery="${i}"><img src="${g.src}" alt=""><button class="del" data-gallery-del="${i}">✕</button></div>`).join('')}</div></div>`}
function viewBookmarks(){return`<div class="card page"><div class="page-head"><div class="page-title">Закладки</div></div><div class="empty">Пока пусто</div></div>`}
function viewSettings(){
  const clickBtns=[
    {id:'ripple',label:'Ripple',icon:'💧'},{id:'glow',label:'Glow',icon:'✨'},{id:'pulse',label:'Pulse',icon:'🔴'},
    {id:'gold',label:'Gold',icon:'👑'},{id:'rainbow',label:'Rainbow',icon:'🌈'},{id:'hearts',label:'Сердца',icon:'❤️'},
    {id:'stars',label:'Звёзды',icon:'⭐'},{id:'fire',label:'Огонь',icon:'🔥'},{id:'none',label:'Убрать',icon:'🚫'},
    {id:'rose',label:'Розы',icon:'🌹'},{id:'cherry',label:'Сакура',icon:'🌸'},{id:'doll',label:'Кукла',icon:'🎀'},
    {id:'pinkheart',label:'Роз.сердца',icon:'💖'},{id:'unicorn',label:'Единорог',icon:'🦄'},{id:'butterfly',label:'Бабочки',icon:'🦋'},
    {id:'pinksparkle',label:'Блёстки',icon:'💕'}
  ].map(c=>`<button class="theme-btn ${state.clickEffect===c.id?'active':''}" data-set-click="${c.id}" style="flex-direction:column;padding:10px 6px"><div style="font-size:20px">${c.icon}</div><div style="font-size:11px;font-weight:700">${c.label}</div></button>`).join('');
  return`<div class="card page"><div class="page-head"><div class="page-title">Настройки</div></div><div class="setting-row"><div class="grow"><div class="setting-name">Тема</div></div><div style="display:flex;gap:8px"><button class="theme-btn ${state.theme==='dark'?'active':''}" data-theme="dark">🌙 Тёмная</button><button class="theme-btn ${state.theme==='light'?'active':''}" data-theme="light">☀️ Светлая</button></div></div><div class="setting-row" style="flex-direction:column;align-items:flex-start;gap:10px"><div><div class="setting-name">✨ Эффект клика</div><div class="setting-sub">Анимация при нажатии в любом месте</div></div><div style="display:grid;grid-template-columns:repeat(auto-fill,minmax(90px,1fr));gap:8px;width:100%">${clickBtns}</div></div><div style="padding:16px 4px;display:flex;flex-direction:column;gap:10px"><button class="btn-primary" id="restoreAdminBtn" style="width:100%;justify-content:center;display:flex;align-items:center;gap:8px;background:linear-gradient(135deg,#ff3b30,#c43028)">👑 Восстановить Admin</button><button class="btn-primary" id="restoreVipBtn" style="width:100%;justify-content:center;display:flex;align-items:center;gap:8px;background:linear-gradient(135deg,#ffd700,#ff9500);color:#000">👑 Восстановить VIP</button><button class="btn-ghost" id="settingsEdit">Редактировать профиль</button><button class="btn-ghost" id="settingsDeleteAccount" style="width:100%;color:var(--red);border-color:var(--red-line)">🗑 Удалить мой аккаунт</button></div></div>`;
}

function forceVisible(){const m=document.getElementById('main');if(!m)return;m.style.setProperty('opacity','1','important');m.style.setProperty('visibility','visible','important');m.style.setProperty('display','flex','important')}

function render(){
  try{renderHeader()}catch(e){console.error('[header]',e)}
  try{renderMenu()}catch(e){console.error('[menu]',e)}
  try{renderRight()}catch(e){console.error('[right]',e)}
  try{renderPlayer()}catch(e){console.error('[player]',e)}
  try{
    switch(state.view||'home'){
      case'music':main.innerHTML=viewMusic();break;
      case'games':main.innerHTML=viewGames();break;
      case'market':main.innerHTML=viewMarket();break;
      case'stickers':main.innerHTML=viewStickers();break;
      case'codes':main.innerHTML=viewCodes();break;
      case'profile':main.innerHTML=viewProfile();break;
      case'user-profile':main.innerHTML=state.viewingAccount?viewUserProfile(state.viewingAccount):'<div class="card page"><div class="empty">Не выбран</div></div>';break;
      case'people':main.innerHTML=viewPeople();break;
      case'messages':main.innerHTML=viewMessages();break;
      case'friends':main.innerHTML=viewFriends();break;
      case'communities':main.innerHTML=viewCommunities();break;
      case'gallery':main.innerHTML=viewGallery();break;
      case'bookmarks':main.innerHTML=viewBookmarks();break;
      case'settings':main.innerHTML=viewSettings();break;
      default:main.innerHTML=viewFeed();
    }
  }catch(e){console.error('[render]',e);main.innerHTML='<div class="card page"><div class="empty">Ошибка: '+esc(e.message)+'</div></div>'}
  forceVisible();
  try{afterRender()}catch(e){console.error('[afterRender]',e)}
}

function afterRender(){
  try{
    if(state.view==='games'&&state.currentGame)initGame(state.currentGame);
    const pub=document.getElementById('publishBtn');if(pub)pub.onclick=publishPost;
    const rcs=document.getElementById('removeComposerSticker');if(rcs)rcs.onclick=()=>{state.composerSticker=null;render()};
    const rcm=document.getElementById('removeComposerMedia');if(rcm)rcm.onclick=()=>{state.composerMedia=null;render()};
    const ai=document.getElementById('audioInput');if(ai)ai.onchange=e=>handleComposerMedia(e,'audio');
    const vi=document.getElementById('videoInput');if(vi)vi.onchange=e=>handleComposerMedia(e,'video');
    const gi=document.getElementById('galleryInput');if(gi)gi.onchange=handleGalleryUpload;
    const ep=document.getElementById('editProfileBtn');if(ep)ep.onclick=openProfileModal;
    const se=document.getElementById('settingsEdit');if(se)se.onclick=openProfileModal;
    const ra=document.getElementById('restoreAdminBtn');if(ra)ra.onclick=restoreAdmin;
    const rv=document.getElementById('restoreVipBtn');if(rv)rv.onclick=restoreVIP;
    const na=document.getElementById('newAccountBtn');if(na)na.onclick=createNewAccount;
    const ab=document.getElementById('accountsBtn');if(ab)ab.onclick=openAccountsModal;
    const ib=document.getElementById('ideaBtn');if(ib)ib.onclick=openIdeaModal;
    const cb=document.getElementById('codeActivateBtn');if(cb)cb.onclick=activateCodeFromInput;
    const ms=document.getElementById('musicSearchInput');if(ms&&!ms.dataset.bound){ms.dataset.bound='1';ms.addEventListener('input',()=>{state.musicQuery=ms.value;render()})}
    const cpu=document.getElementById('copyProfileUrlBtn');if(cpu)cpu.onclick=()=>{const url=document.getElementById('profileUrl').textContent;if(navigator.clipboard)navigator.clipboard.writeText(url).then(()=>toast('✅ Ссылка скопирована')).catch(()=>toast('Ссылка: '+url));else toast('Ссылка: '+url)};
    const sda=document.getElementById('settingsDeleteAccount');if(sda)sda.onclick=openDeleteModal;
  }catch(e){console.error('[afterRender inner]',e)}
}

/* === УДАЛЕНИЕ АККАУНТА === */
let deleteTargetId=null;
function openDeleteModal(){
  const id=getAccountId();
  if(!id){toast('Нет активного аккаунта');return}
  const db=getAccountsDb();
  const acc=db[id];
  if(!acc){toast('Аккаунт не найден');return}
  deleteTargetId=id;
  document.getElementById('deleteAccName').textContent=acc.name||'—';
  document.getElementById('deleteConfirmInput').value='';
  document.getElementById('confirmDeleteModal').hidden=false;
  setTimeout(()=>document.getElementById('deleteConfirmInput').focus(),100);
}
function closeDeleteModal(){document.getElementById('confirmDeleteModal').hidden=true;deleteTargetId=null}
function confirmDeleteAccount(){
  const input=document.getElementById('deleteConfirmInput').value.trim();
  if(!deleteTargetId){closeDeleteModal();return}
  const db=getAccountsDb();
  const acc=db[deleteTargetId];
  if(!acc){closeDeleteModal();return}
  if(input!==(acc.name||'')){toast('❌ Имя не совпадает');return}
  delete db[deleteTargetId];
  saveAccountsDb(db);
  try{localStorage.removeItem('vk_current_account_id')}catch(e){}
  try{localStorage.removeItem('vk_profile')}catch(e){}
  try{localStorage.removeItem('vk_registered')}catch(e){}
  state.me={name:'',initials:'??',status:'',city:'',phone:'',email:'',about:'',role:null,coverStyle:'none',avatarStyle:'none',isAdmin:false,vipUntil:0,gender:null,avatarPhoto:null,accountId:null};
  state.coins=0;state.voices=0;state.purchased=[];state.purchasedPacks=[];state.usedCodes=[];state.gallery=[];state.media=[];state.friends=[];state.messages={};
  persistProfile();persistCoins();persistVoices();persistPurchased();persistPacks();persistCodes();persistGallery();persistMedia();persistFriends();persistMessages();
  closeDeleteModal();
  showRegistration();
  toast('🗑 Аккаунт удалён');
}

/* === ПРОФИЛЬ/АККАУНТЫ === */
let pendingRole=null;
let pendingAvatarPhoto=null;
let pendingAvatarStyle='none';
let pendingCoverStyle='none';
function renderAvatarPreview(){const el=document.getElementById('avatarPreview');if(!el)return;if(pendingAvatarPhoto){el.innerHTML=`<img src="${pendingAvatarPhoto}" alt="">`}else{const name=document.getElementById('fName')?.value||state.me.name||'';el.textContent=deriveInitials(name)}const wrap=document.getElementById('avatarPreviewWrap');if(wrap){wrap.className='avatar-wrap style-'+pendingAvatarStyle}}
function renderRolePicker(){const el=document.getElementById('rolePicker');if(!el)return;el.innerHTML=`<button type="button" class="theme-btn ${!pendingRole?'active':''}" data-set-role="">Без роли</button>`+ROLES.map(r=>{const active=pendingRole===r.id;const style=active?`background:${r.bg};color:${r.color};border-color:transparent;${r.border?'border:'+r.border+';':''}`:'';return`<button type="button" class="theme-btn ${active?'active':''}" data-set-role="${r.id}" style="${style}">${r.emoji} ${esc(r.name)}</button>`}).join('')}
function renderAvatarStylePicker(){const el=document.getElementById('avatarStylePicker');if(!el)return;el.innerHTML=AVATAR_STYLES.map(s=>{const active=pendingAvatarStyle===s.id;return`<div data-set-avatar-style="${s.id}" style="cursor:pointer;padding:8px 4px;border-radius:10px;border:2px solid ${active?'var(--red)':'var(--border)'};background:${active?'var(--red-soft)':'var(--surface-2)'};display:flex;flex-direction:column;align-items:center;gap:5px"><div class="avatar-wrap style-${s.id}" style="width:32px;height:32px"><div class="avatar a28">${esc(state.me.initials||'??')}</div></div><div style="font-size:9.5px;color:${active?'var(--red)':'var(--muted)'};text-align:center;line-height:1.2">${esc(s.label)}</div></div>`}).join('')}
function renderCoverStylePicker(){const el=document.getElementById('coverStylePicker');if(!el)return;el.innerHTML=COVER_STYLES.map(s=>{const active=pendingCoverStyle===s.id;return`<div data-set-cover-style="${s.id}" style="cursor:pointer;padding:6px 4px;border-radius:10px;border:2px solid ${active?'var(--red)':'var(--border)'};background:${active?'var(--red-soft)':'var(--surface-2)'};display:flex;flex-direction:column;align-items:center;gap:4px"><div class="cover style-${s.id}" style="width:100%;height:30px;border-radius:6px"></div><div style="font-size:9.5px;color:${active?'var(--red)':'var(--muted)'};text-align:center;line-height:1.2">${esc(s.label)}</div></div>`}).join('')}
function openProfileModal(){pendingRole=state.me.role||null;pendingAvatarPhoto=state.me.avatarPhoto||null;pendingAvatarStyle=state.me.avatarStyle||'none';pendingCoverStyle=state.me.coverStyle||'none';document.getElementById('fName').value=state.me.name||'';document.getElementById('fStatus').value=state.me.status||'';document.getElementById('fCity').value=state.me.city||'';document.getElementById('fPhone').value=state.me.phone||'';document.getElementById('fEmail').value=state.me.email||'';document.getElementById('fAbout').value=state.me.about||'';renderRolePicker();renderAvatarPreview();renderAvatarStylePicker();renderCoverStylePicker();if(modal)modal.hidden=false}
function closeProfileModal(){if(modal)modal.hidden=true}

function openAccountsModal(){
  const db=getAccountsDb();
  const ids=Object.keys(db);
  const curId=localStorage.getItem('vk_current_account_id');
  const list=document.getElementById('accountsList');
  if(!ids.length){list.innerHTML='<div class="empty" style="padding:24px">Создайте второй аккаунт</div>'}
  else{
    list.innerHTML=ids.map(id=>{
      const acc=db[id];if(!acc)return'';
      const isCur=id===curId;
      const initials=acc.name?acc.name.split(' ').map(w=>w[0]).join('').slice(0,2).toUpperCase():'??';
      const isAdminFlag=acc.data?.me?.isAdmin;
      return`<div class="simple-row" style="cursor:default;flex-wrap:wrap"><div class="avatar a44">${acc.data?.me?.avatarPhoto?`<img src="${acc.data.me.avatarPhoto}" alt="">`:esc(initials)}</div><div class="grow"><div class="simple-name">${esc(acc.name)} ${isAdminFlag?'<span class="admin-badge">Admin</span>':''} ${isCur?'<span style="color:var(--red);font-size:11px">✓</span>':''}</div><div class="simple-sub">${esc(acc.phone||acc.email||'—')}</div></div><div style="display:flex;gap:6px;flex-wrap:wrap">${isCur?'':`<button class="row-btn" data-switch-account="${esc(id)}">Войти</button>`}<button class="row-btn" data-delete-account="${esc(id)}" style="color:var(--red);border-color:var(--red-line)">🗑</button></div></div>`;
    }).join('');
  }
  document.getElementById('accountsModal').hidden=false;
}
function closeAccountsModal(){document.getElementById('accountsModal').hidden=true}
function switchAccount(id){saveCurrentAccountToDb();if(loadAccountFromDb(id)){closeAccountsModal();render();toast('👋 Вы вошли как '+state.me.name)}else{toast('❌ Не удалось загрузить')}}
function deleteAccountById(id){
  const db=getAccountsDb();
  const acc=db[id];if(!acc){toast('Не найден');return}
  const curId=localStorage.getItem('vk_current_account_id');
  const isCur=id===curId;
  const confirmText=prompt('Введите имя аккаунта для удаления ('+acc.name+'):');
  if(confirmText!==acc.name){toast('❌ Имя не совпадает');return}
  delete db[id];
  saveAccountsDb(db);
  if(isCur){
    try{localStorage.removeItem('vk_current_account_id')}catch(e){}
    try{localStorage.removeItem('vk_profile')}catch(e){}
    try{localStorage.removeItem('vk_registered')}catch(e){}
    state.me={name:'',initials:'??',status:'',city:'',phone:'',email:'',about:'',role:null,coverStyle:'none',avatarStyle:'none',isAdmin:false,vipUntil:0,gender:null,avatarPhoto:null,accountId:null};
    state.coins=0;state.voices=0;state.purchased=[];state.purchasedPacks=[];state.usedCodes=[];state.gallery=[];state.media=[];state.friends=[];state.messages={};
    persistProfile();persistCoins();persistVoices();persistPurchased();persistPacks();persistCodes();persistGallery();persistMedia();persistFriends();persistMessages();
    closeAccountsModal();
    showRegistration();
    toast('🗑 Аккаунт удалён');
  }else{
    openAccountsModal();
    toast('🗑 Аккаунт удалён');
  }
}

let newAccGender=null;
function createNewAccount(){newAccGender=null;document.getElementById('newAccName').value='';document.getElementById('newAccPhone').value='';document.getElementById('newAccEmail').value='';document.getElementById('newAccPassword').value='';document.querySelectorAll('[data-newacc-gender]').forEach(x=>{x.style.borderColor='var(--border)';x.style.background='var(--surface-2)'});document.getElementById('newAccountModal').hidden=false;setTimeout(()=>document.getElementById('newAccName').focus(),100)}
function closeNewAccountModal(){document.getElementById('newAccountModal').hidden=true}
function createNewAccountSubmit(){const name=document.getElementById('newAccName').value.trim();const phone=document.getElementById('newAccPhone').value.trim();const email=document.getElementById('newAccEmail').value.trim();const password=document.getElementById('newAccPassword').value;if(!name){toast('Введите имя');return}if(phone.replace(/\D/g,'').length<10){toast('Введите телефон');return}if(!/^[^\s@]+@[^\s@]+\.[^\s@]+$/.test(email)){toast('Введите email');return}if(password.length<6){toast('Пароль мин. 6');return}if(!newAccGender){toast('Выберите пол');return}const id=phone;const db=getAccountsDb();if(db[id]){toast('Такой телефон уже есть');return}if(state.me&&(state.me.phone||state.me.email))saveCurrentAccountToDb();state.me={name,initials:deriveInitials(name),status:'',city:'',about:'',role:null,coverStyle:'none',avatarStyle:'none',isAdmin:false,vipUntil:0,gender:newAccGender,avatarPhoto:null,phone,email,accountId:null};state.coins=0;state.voices=0;state.purchased=[];state.purchasedPacks=[];state.usedCodes=[];state.gallery=[];state.media=[];state.friends=[];state.messages={};const newDb=getAccountsDb();newDb[id]={id,name,phone,email,gender:newAccGender,password,data:{me:{...state.me},coins:0,voices:0,purchased:[],purchasedPacks:[],usedCodes:[],gallery:[],media:[],posts:[],friends:[],messages:{}}};saveAccountsDb(newDb);try{localStorage.setItem('vk_current_account_id',id)}catch(e){}persistProfile();persistCoins();persistVoices();persistPurchased();persistPacks();persistCodes();persistGallery();persistMedia();persistFriends();persistMessages();localStorage.setItem('vk_registered','1');closeNewAccountModal();document.getElementById('genderModal').hidden=true;render();toast('🎉 Аккаунт создан!')}

function openIdeaModal(){document.getElementById('ideaText').value='';document.getElementById('ideaCounter').textContent='0/500';document.getElementById('ideaModal').hidden=false;setTimeout(()=>document.getElementById('ideaText').focus(),100)}
function closeIdeaModal(){document.getElementById('ideaModal').hidden=true}
function sendIdea(){const t=document.getElementById('ideaText').value.trim();if(t.length<5){toast('Слишком коротко');return}const ideas=JSON.parse(localStorage.getItem('vk_project_ideas')||'[]');ideas.push({text:t,author:state.me.name,phone:state.me.phone,time:Date.now()});try{localStorage.setItem('vk_project_ideas',JSON.stringify(ideas))}catch(e){}closeIdeaModal();toast('✅ Идея отправлена')}

/* === СООБЩЕНИЯ === */
let currentChatId=null;
function openChat(userId){
  try{
    const db=getAccountsDb();const acc=db[userId];
    if(!acc){toast('Пользователь не найден');return}
    currentChatId=userId;
    const titleEl=document.getElementById('chatTitle');if(titleEl)titleEl.textContent='✉️ '+acc.name;
    if(!state.messages[userId])state.messages[userId]=[];
    state.messages[userId].forEach(m=>m.read=true);
    persistMessages();saveCurrentAccountToDb();
    renderChat();
    const chatModal=document.getElementById('chatModal');if(chatModal)chatModal.hidden=false;
    const inp=document.getElementById('chatInput');if(inp)setTimeout(()=>inp.focus(),100);
  }catch(e){console.error('[openChat]',e);toast('Ошибка открытия чата')}
}
function closeChat(){const m=document.getElementById('chatModal');if(m)m.hidden=true;const p=document.getElementById('chatEmojiPanel');if(p)p.style.display='none';currentChatId=null;render()}
function renderChat(){
  if(!currentChatId)return;
  const body=document.getElementById('chatBody');if(!body)return;
  const msgs=state.messages[currentChatId]||[];
  body.innerHTML=msgs.length?msgs.map(m=>{
    if(m.type==='voice' && m.audio){
      return`<div style="align-self:${m.from==='me'?'flex-end':'flex-start'};max-width:80%;padding:8px 12px;border-radius:12px;background:${m.from==='me'?'var(--red)':'var(--surface-2)'};color:${m.from==='me'?'#fff':'var(--text)'};font-size:13.5px"><div style="font-size:16px;margin-bottom:4px">🎤 Голосовое (${m.duration||'?'}с)</div><audio controls src="${m.audio}" style="width:100%;max-width:240px"></audio><div style="font-size:10px;opacity:.65;margin-top:3px">${esc(m.time||'')}</div></div>`;
    }
    return`<div style="align-self:${m.from==='me'?'flex-end':'flex-start'};max-width:80%;padding:8px 12px;border-radius:12px;background:${m.from==='me'?'var(--red)':'var(--surface-2)'};color:${m.from==='me'?'#fff':'var(--text)'};font-size:13.5px;word-break:break-word"><div>${esc(m.text)}</div><div style="font-size:10px;opacity:.65;margin-top:3px">${esc(m.time||'')}</div></div>`;
  }).join(''):'<div class="empty" style="font-size:13px">Начните переписку — напишите сообщение или отправьте голосовое</div>';
  body.scrollTop=body.scrollHeight;
}
function sendChatMessage(){
  if(!currentChatId)return;
  const inp=document.getElementById('chatInput');const text=inp.value.trim();
  if(!text)return;
  if(!state.messages[currentChatId])state.messages[currentChatId]=[];
  state.messages[currentChatId].push({from:'me',text,time:nowTime(),read:true});
  inp.value='';persistMessages();
  const cid=currentChatId;const myId=getAccountId();const db=getAccountsDb();
  if(db[cid] && db[cid].data){
    if(!db[cid].data.messages) db[cid].data.messages={};
    if(!db[cid].data.messages[myId]) db[cid].data.messages[myId]=[];
    db[cid].data.messages[myId].push({from:'them',text,time:nowTime(),read:false,peerName:state.me.name||'Вы'});
    saveAccountsDb(db);
  }
  saveCurrentAccountToDb();renderChat();toast('✉️ Сообщение отправлено');
}

let mediaRecorder=null;let recordedChunks=[];let recStartTime=0;let recTimer=null;
function showMicPermissionPrompt(){return new Promise((resolve)=>{const m=document.getElementById('micPermissionModal');if(!m){resolve(false);return}const allow=document.getElementById('micAllow');const deny=document.getElementById('micDeny');const cleanup=()=>{allow.onclick=null;deny.onclick=null;m.hidden=true};allow.onclick=()=>{cleanup();resolve(true)};deny.onclick=()=>{cleanup();resolve(false)};m.hidden=false})}
async function startVoiceRecording(){
  if(!currentChatId){toast('Откройте чат');return}
  try{
    if(!navigator.mediaDevices||!navigator.mediaDevices.getUserMedia){toast('❌ Микрофон не поддерживается');return}
    const ok=await showMicPermissionPrompt();
    if(!ok){toast('Микрофон запрещён');return}
    const stream=await navigator.mediaDevices.getUserMedia({audio:true});
    recordedChunks=[];
    mediaRecorder=new MediaRecorder(stream);
    mediaRecorder.ondataavailable=(e)=>{if(e.data.size>0)recordedChunks.push(e.data)};
    mediaRecorder.onstop=async()=>{
      stream.getTracks().forEach(t=>t.stop());
      const dur=Math.round((Date.now()-recStartTime)/1000);
      const blob=new Blob(recordedChunks,{type:mediaRecorder.mimeType||'audio/webm'});
      if(blob.size<800){toast('⚠️ Слишком короткая запись');restoreVoiceBtn();return}
      const reader=new FileReader();
      reader.onload=async()=>{
        const audioData=reader.result;
        if(!state.messages[currentChatId])state.messages[currentChatId]=[];
        state.messages[currentChatId].push({from:'me',type:'voice',audio:audioData,duration:dur,time:nowTime(),read:true});
        persistMessages();
        const cid=currentChatId;const myId=getAccountId();const db=getAccountsDb();
        if(db[cid] && db[cid].data){
          if(!db[cid].data.messages) db[cid].data.messages={};
          if(!db[cid].data.messages[myId]) db[cid].data.messages[myId]=[];
          db[cid].data.messages[myId].push({from:'them',type:'voice',audio:audioData,duration:dur,time:nowTime(),read:false,peerName:state.me.name||'Вы'});
          saveAccountsDb(db);
        }
        saveCurrentAccountToDb();renderChat();restoreVoiceBtn();
        toast('🎤 Голосовое отправлено ('+dur+'с)');
      };
      reader.readAsDataURL(blob);
    };
    recStartTime=Date.now();
    mediaRecorder.start();
    const btn=document.getElementById('chatVoiceBtn');
    if(btn){btn.textContent='⏹';btn.style.background='var(--red)';btn.style.color='#fff';btn.dataset.recording='1'}
    toast('🔴 Запись... нажмите ⏹ чтобы остановить');
    recTimer=setInterval(()=>{const t=Math.round((Date.now()-recStartTime)/1000);const btn=document.getElementById('chatVoiceBtn');if(btn)btn.textContent='⏹ '+t+'с'},500);
  }catch(err){console.error(err);toast('❌ Ошибка микрофона: '+err.message);restoreVoiceBtn()}
}
function stopVoiceRecording(){if(mediaRecorder&&mediaRecorder.state!=='inactive'){mediaRecorder.stop()}if(recTimer){clearInterval(recTimer);recTimer=null}}
function restoreVoiceBtn(){if(recTimer){clearInterval(recTimer);recTimer=null}const btn=document.getElementById('chatVoiceBtn');if(btn){btn.textContent='🎤';btn.style.background='var(--surface-2)';btn.style.color='var(--text)';btn.dataset.recording='0'}}

/* === ПРОЧЕЕ === */
function handleComposerMedia(e,type){const file=e.target.files[0];if(!file)return;if(file.size>3*1024*1024){toast('⚠️ Файл > 3 MB');e.target.value='';return}const reader=new FileReader();reader.onload=()=>{state.composerMedia={type,src:reader.result,name:file.name};render();toast(type==='audio'?'🎵 Аудио':'🎬 Видео')};reader.readAsDataURL(file)}
function publishPost(){const ta=document.getElementById('postInput');const text=ta?ta.value.trim():'';const sticker=state.composerSticker;const media=state.composerMedia;if(!text&&!sticker&&!media){toast('Введите текст');return}posts.unshift({id:Date.now(),author:state.me.name||'Гость',initials:state.me.initials||'??',time:'только что',text,sticker,media:media?{...media}:null,reactions:{'❤️':0},myReaction:null,comments:0,shares:0,mine:true});if(media){state.media.push({type:media.type,src:media.src,name:media.name});persistMedia()}state.composerSticker=null;state.composerMedia=null;persistPosts();saveCurrentAccountToDb();render();toast('Опубликовано')}
function handlePostAction(btn){const postEl=btn.closest('.post');if(!postEl)return;const post=posts.find(p=>p.id===+postEl.dataset.id);if(!post)return;const act=btn.dataset.act;if(act==='like'){if(post.myReaction){post.myReaction=null;post.reactions['❤️']=Math.max(0,(post.reactions['❤️']||0)-1)}else{post.myReaction='❤️';post.reactions['❤️']=(post.reactions['❤️']||0)+1}btn.classList.toggle('liked',!!post.myReaction);const cnt=btn.querySelector('span:last-child');if(cnt)cnt.textContent=fmtNum(Object.values(post.reactions).reduce((a,b)=>a+b,0));persistPosts();saveCurrentAccountToDb()}}
function handleGalleryUpload(e){const files=[...e.target.files];if(!files.length)return;let done=0;files.forEach(file=>{if(file.size>3*1024*1024){toast('⚠️ Слишком большой');return}const r=new FileReader();r.onload=()=>{state.gallery.push({src:r.result});done++;if(done===files.length){persistGallery();saveCurrentAccountToDb();render();toast('Фото добавлено')}};r.readAsDataURL(file)})}
function openGalleryViewer(i){const g=state.gallery[i];if(!g)return;document.getElementById('gvImg').src=g.src;document.getElementById('galleryViewer').hidden=false}

function buyCoinPack(packId){const pack=COIN_PACKS.find(p=>p.id===packId);if(!pack)return;state.coins+=pack.coins;persistCoins();saveCurrentAccountToDb();toast(`+${pack.coins} BkV`);render()}
function buyVIP(days,currency){days=days||30;const price=VIP_PRICES[days];if(!price)return;if(isVIP()){toast('VIP уже активен');return}if(currency==='coins'){if(state.coins<price.coins){toast('Недостаточно BkV');return}state.coins-=price.coins;persistCoins();grantVIP(days);saveCurrentAccountToDb();toast(`👑 VIP на ${price.label}!`);render();return}openPaymentModal({type:'vip',days,label:price.label,amount:price.rub})}
function buyStickerPack(id){const pack=getPack(id);if(!pack)return;if(hasPack(id)){toast('Уже куплено');return}const price=packPrice(pack);if(state.voices<price){toast(`Недостаточно голосов (${price})`);return}state.voices-=price;state.purchasedPacks.push(id);persistVoices();persistPacks();saveCurrentAccountToDb();toast(`Куплено: ${pack.name}`);render()}

function openStickerPicker(){if(!state.purchasedPacks.length){toast('Сначала купите стикерпак');setView('stickers');return}const body=document.getElementById('stickerPickerBody');if(!body)return;body.innerHTML=state.purchasedPacks.map(id=>{const p=getPack(id);if(!p)return'';return`<div style="display:flex;flex-direction:column;gap:9px;margin-bottom:16px"><div style="font-size:12.5px;font-weight:700;color:var(--muted);text-transform:uppercase">${esc(p.name)}</div><div style="display:flex;flex-wrap:wrap;gap:9px">${p.stickers.map(s=>`<div class="sticker-tile ${p.theme==='black'?'theme-black':''}" data-pick-sticker="${esc(s)}">${s}</div>`).join('')}</div></div>`}).join('');document.getElementById('stickerPickerModal').hidden=false}
function pickSticker(s){document.getElementById('stickerPickerModal').hidden=true;state.composerSticker=s;render();toast('Стикер добавлен')}

let playerTimer=null;
function renderPlayer(){if(!playerEl)return;if(!state.currentTrack){playerEl.classList.remove('show');playerEl.innerHTML='';return}const t=getTrack(state.currentTrack);if(!t){playerEl.classList.remove('show');playerEl.innerHTML='';return}const pct=Math.min(100,(state.elapsed/t.dur)*100);playerEl.classList.add('show');playerEl.innerHTML=`<div class="player-inner"><div class="player-row"><div class="player-track"><div class="avatar a36">${esc(state.me.initials)}</div><div style="min-width:0"><div class="player-title">${esc(t.title)}</div><div class="player-artist">${esc(t.artist)}</div></div></div><button class="player-skip" data-player="prev">⏮</button><button class="player-btn" data-player="toggle">${state.playing?'⏸':'▶'}</button><button class="player-skip" data-player="next">⏭</button><div class="player-bar" data-player="seek"><div class="player-fill" style="width:${pct}%"></div></div><div class="player-time">${fmtDur(state.elapsed)} / ${fmtDur(t.dur)}</div></div></div>`}
function updatePlayerProgress(){if(!state.currentTrack)return;const t=getTrack(state.currentTrack);const fill=playerEl.querySelector('.player-fill');const time=playerEl.querySelector('.player-time');if(fill)fill.style.width=Math.min(100,(state.elapsed/t.dur)*100)+'%';if(time)time.textContent=fmtDur(state.elapsed)+' / '+fmtDur(t.dur)}
function startPlayerTimer(){stopPlayerTimer();playerTimer=setInterval(()=>{if(!state.playing)return;const t=getTrack(state.currentTrack);if(!t)return;state.elapsed++;if(state.elapsed>=t.dur){nextTrack();return}updatePlayerProgress()},1000)}
function stopPlayerTimer(){if(playerTimer){clearInterval(playerTimer);playerTimer=null}}
function playTrack(id){if(state.currentTrack===id){togglePlay();return}state.currentTrack=id;state.elapsed=0;state.playing=true;startAudio(id);startPlayerTimer();render()}
function togglePlay(){if(!state.currentTrack)return;state.playing=!state.playing;if(state.playing){startAudio(state.currentTrack);startPlayerTimer()}else{stopAudio();stopPlayerTimer()}renderPlayer()}
function nextTrack(){if(!state.currentTrack)return;const idx=music.findIndex(t=>t.id===state.currentTrack);const next=music[(idx+1)%music.length];state.currentTrack=next.id;state.elapsed=0;state.playing=true;startAudio(next.id);startPlayerTimer();render()}
function prevTrack(){if(!state.currentTrack)return;const idx=music.findIndex(t=>t.id===state.currentTrack);const prev=music[(idx-1+music.length)%music.length];state.currentTrack=prev.id;state.elapsed=0;state.playing=true;startAudio(prev.id);startPlayerTimer();render()}

let gameCleanup=null;
function initGame(id){if(gameCleanup){try{gameCleanup()}catch(e){}gameCleanup=null}const c=document.getElementById('gameContainer');if(!c)return;if(id==='2048')init2048(c);else if(id==='snake')initSnake(c);else if(id==='memory')initMemory(c);else if(id==='simon')initSimon(c);else if(id==='ttt')initTTT(c);else if(id==='mines')initMines(c);else if(id==='tetris')initTetris(c);else if(id==='breakout')initBreakout(c);else if(id==='reaction')initReaction(c);else if(id==='guess')initGuess(c)}
function exitGame(){if(gameCleanup){try{gameCleanup()}catch(e){}gameCleanup=null}state.currentGame=null;render()}
function init2048(c){let g,s,o;const T=x=>x[0].map((_,i)=>x.map(r=>r[i]));c.innerHTML=`<div class="game-topbar"><div class="game-score">Очки: <b id="gS">0</b></div><button class="game-restart" id="gR">Заново</button></div><div style="display:grid;grid-template-columns:repeat(4,78px);grid-template-rows:repeat(4,78px);gap:9px;background:var(--surface-2);padding:9px;border-radius:15px" id="gG"></div><div class="game-status" id="gSt"></div>`;const GE=c.querySelector('#gG'),SE=c.querySelector('#gS'),STE=c.querySelector('#gSt');function sp(){const e=[];for(let r=0;r<4;r++)for(let cc=0;cc<4;cc++)if(!g[r][cc])e.push([r,cc]);if(!e.length)return;const[r,cc]=e[Math.floor(Math.random()*e.length)];g[r][cc]=Math.random()<.9?2:4}function sl(row){const arr=row.filter(v=>v);const out=[];for(let i=0;i<arr.length;i++){if(arr[i]===arr[i+1]){out.push(arr[i]*2);s+=arr[i]*2;i++}else out.push(arr[i])}while(out.length<4)out.push(0);return out}function co(){for(let r=0;r<4;r++)for(let cc=0;cc<4;cc++){if(!g[r][cc])return false;if(cc<3&&g[r][cc]===g[r][cc+1])return false;if(r<3&&g[r][cc]===g[r+1][cc])return false}return true}function pt(){GE.innerHTML=g.flat().map(v=>`<div style="background:var(--surface-3);border-radius:9px;display:flex;align-items:center;justify-content:center;font-weight:800;font-size:24px;color:var(--text)">${v||''}</div>`).join('');SE.textContent=s;STE.textContent=o?'Игра окончена':''}function mv(d){if(o)return;const b=JSON.stringify(g);if(d==='left')g=g.map(sl);else if(d==='right')g=g.map(r=>sl(r.slice().reverse()).reverse());else if(d==='up')g=T(T(g).map(sl));else if(d==='down')g=T(T(g).map(r=>sl(r.slice().reverse()).reverse()));if(JSON.stringify(g)!==b)sp();o=co();pt()}function rs(){g=Array.from({length:4},()=>[0,0,0,0]);s=0;o=false;sp();sp();pt()}const kh=e=>{const m={ArrowLeft:'left',ArrowRight:'right',ArrowUp:'up',ArrowDown:'down'};if(m[e.key]){e.preventDefault();mv(m[e.key])}};window.addEventListener('keydown',kh);c.querySelector('#gR').onclick=rs;rs();gameCleanup=()=>window.removeEventListener('keydown',kh)}
function initSnake(c){c.innerHTML=`<div class="game-topbar"><div class="game-score">Счёт: <b id="sS">0</b></div><button class="game-restart" id="sR">Заново</button></div><canvas id="sC" width="400" height="400" style="background:#0a0a0a;border-radius:15px"></canvas><div class="game-status" id="sSt"></div>`;const cv=c.querySelector('#sC'),cx=cv.getContext('2d'),ce=20,co=20,ro=20,SE=c.querySelector('#sS'),STE=c.querySelector('#sSt');let sn,di,fo,sc,al,ti;function pf(){do{fo={x:Math.floor(Math.random()*co),y:Math.floor(Math.random()*ro)}}while(sn.some(s=>s.x===fo.x&&s.y===fo.y))}function dr(){cx.fillStyle='#0a0a0a';cx.fillRect(0,0,400,400);cx.fillStyle='#ff3b30';cx.beginPath();cx.arc(fo.x*ce+ce/2,fo.y*ce+ce/2,ce/2-2,0,Math.PI*2);cx.fill();sn.forEach((s,i)=>{cx.fillStyle=i===0?'#fff':'#ff3b30';cx.fillRect(s.x*ce+1,s.y*ce+1,ce-2,ce-2)})}function tk(){if(!al)return;const h={x:sn[0].x+di.x,y:sn[0].y+di.y};if(h.x<0||h.y<0||h.x>=co||h.y>=ro||sn.some(s=>s.x===h.x&&s.y===h.y)){al=false;STE.textContent='Игра окончена';if(ti)clearInterval(ti);return}sn.unshift(h);if(h.x===fo.x&&h.y===fo.y){sc++;SE.textContent=sc;pf()}else sn.pop();dr()}function rs(){sn=[{x:10,y:10}];di={x:1,y:0};sc=0;al=true;SE.textContent=0;STE.textContent='';pf();if(ti)clearInterval(ti);dr();ti=setInterval(tk,130)}const kh=e=>{const k=e.key;if((k==='ArrowUp'||k==='w')&&di.y===0){di={x:0,y:-1};e.preventDefault()}else if((k==='ArrowDown'||k==='s')&&di.y===0){di={x:0,y:1};e.preventDefault()}else if((k==='ArrowLeft'||k==='a')&&di.x===0){di={x:-1,y:0};e.preventDefault()}else if((k==='ArrowRight'||k==='d')&&di.x===0){di={x:1,y:0};e.preventDefault()}};window.addEventListener('keydown',kh);c.querySelector('#sR').onclick=rs;rs();gameCleanup=()=>{window.removeEventListener('keydown',kh);if(ti)clearInterval(ti)}}
function initMemory(c){const em=['🍎','🍌','🍇','🍓','🍒','🍑','🥝','🍍'];let dk,fi,lo,mo,ma;c.innerHTML=`<div class="game-topbar"><div class="game-score">Ходы: <b id="mM">0</b></div><button class="game-restart" id="mR">Заново</button></div><div style="display:grid;grid-template-columns:repeat(4,86px);gap:9px" id="mG"></div><div class="game-status" id="mSt"></div>`;const G=c.querySelector('#mG'),ME=c.querySelector('#mM'),STE=c.querySelector('#mSt');function pt(){G.innerHTML=dk.map((x,i)=>`<div data-card="${i}" style="width:86px;height:86px;border-radius:13px;background:${x.flipped||x.matched?'rgba(255,59,48,.2)':'#141414'};border:1px solid #242424;display:flex;align-items:center;justify-content:center;font-size:38px;cursor:pointer">${x.flipped||x.matched?x.e:''}</div>`).join('');ME.textContent=mo;if(ma===em.length)STE.textContent='Победа!'}G.addEventListener('click',e=>{const el=e.target.closest('[data-card]');if(!el||lo)return;const i=+el.dataset.card,x=dk[i];if(x.flipped||x.matched)return;x.flipped=true;if(fi===null){fi=i;pt();return}mo++;const a=dk[fi],b=x;if(a.e===b.e){a.matched=b.matched=true;ma++;fi=null;pt()}else{lo=true;pt();setTimeout(()=>{a.flipped=false;b.flipped=false;fi=null;lo=false;pt()},700)}});function rs(){dk=[...em,...em].sort(()=>Math.random()-.5).map((e,i)=>({e,id:i,flipped:false,matched:false}));fi=null;lo=false;mo=0;ma=0;pt()}c.querySelector('#mR').onclick=rs;rs();gameCleanup=()=>{}}
function initSimon(c){const colors=['#ff3b30','#3b8bff','#3bff8b','#ffd23b'];let sq,st,pl,ro;c.innerHTML=`<div class="game-topbar"><div class="game-score">Раунд: <b id="siR">0</b></div><button class="game-restart" id="siRes">Заново</button></div><div style="display:grid;grid-template-columns:repeat(2,130px);grid-template-rows:repeat(2,130px);gap:12px;padding:16px;background:var(--surface-2);border-radius:22px" id="siB">${[0,1,2,3].map(i=>`<button data-simon="${i}" style="border-radius:16px;border:2px solid transparent;cursor:pointer;background:${colors[i]}22"></button>`).join('')}</div><div class="game-status" id="siSt"></div>`;const B=c.querySelector('#siB'),STE=c.querySelector('#siSt'),RE=c.querySelector('#siR');function fl(i,du=300){const btn=B.querySelector(`[data-simon="${i}"]`);if(!btn)return;btn.style.background=colors[i];setTimeout(()=>{btn.style.background=colors[i]+'22'},du)}function ps(){pl=true;STE.textContent='Смотрите...';sq.forEach((v,i)=>setTimeout(()=>fl(v),600*i+300));setTimeout(()=>{pl=false;STE.textContent='Повторите'},600*sq.length+400)}function nr(){ro++;RE.textContent=ro;sq.push(Math.floor(Math.random()*4));st=0;ps()}B.addEventListener('click',e=>{const btn=e.target.closest('[data-simon]');if(!btn||pl)return;const i=+btn.dataset.simon;fl(i,200);if(sq[st]!==i){STE.textContent='Ошибка!';pl=true;return}st++;if(st===sq.length){pl=true;STE.textContent='Верно!';setTimeout(nr,900)}});function rs(){sq=[];st=0;pl=false;ro=0;RE.textContent=0;STE.textContent='';nr()}c.querySelector('#siRes').onclick=rs;rs();gameCleanup=()=>{}}
function initTTT(c){let bo,ov;const hu='X',ai='O';c.innerHTML=`<div class="game-topbar"><div class="game-score">Вы: <b>${hu}</b></div><button class="game-restart" id="tR">Заново</button></div><div style="display:grid;grid-template-columns:repeat(3,100px);grid-template-rows:repeat(3,100px);gap:9px;background:var(--surface-2);padding:9px;border-radius:18px" id="tG"></div><div class="game-status" id="tSt"></div>`;const G=c.querySelector('#tG'),STE=c.querySelector('#tSt');const li=[[0,1,2],[3,4,5],[6,7,8],[0,3,6],[1,4,7],[2,5,8],[0,4,8],[2,4,6]];function wi(b){for(const[a,cx,d]of li){if(b[a]&&b[a]===b[cx]&&b[a]===b[d])return{p:b[a],line:[a,cx,d]}}if(b.every(v=>v))return{p:'draw'};return null}function pt(){const w=wi(bo);G.innerHTML=bo.map((v,i)=>{const wn=w&&w.line&&w.line.includes(i);return`<div data-ttt="${i}" style="width:100px;height:100px;border-radius:11px;background:${wn?'rgba(255,59,48,.2)':'var(--surface-3)'};border:1px solid var(--border);display:flex;align-items:center;justify-content:center;font-size:46px;font-weight:800;cursor:pointer;color:${v==='X'?'var(--red)':'var(--text)'}">${v}</div>`}).join('')}function ce(){const w=wi(bo);if(w){ov=true;if(w.p==='draw')STE.textContent='Ничья';else if(w.p===hu)STE.textContent='Вы победили!';else STE.textContent='ИИ победил';pt();return true}return false}function mm(b,pl){const w=wi(b);if(w){if(w.p===ai)return{score:1};if(w.p===hu)return{score:-1};return{score:0}}let be=pl===ai?{score:-Infinity}:{score:Infinity};for(let i=0;i<9;i++){if(b[i])continue;b[i]=pl;const r=mm(b,pl===ai?hu:ai);b[i]='';if(pl===ai){if(r.score>be.score)be={score:r.score,move:i}}else{if(r.score<be.score)be={score:r.score,move:i}}}return be}function aiM(){if(ov)return;const m=mm(bo.slice(),ai).move;if(m===undefined)return;bo[m]=ai;pt();if(!ce())STE.textContent='Ваш ход'}G.addEventListener('click',e=>{const el=e.target.closest('[data-ttt]');if(!el||ov)return;const i=+el.dataset.ttt;if(bo[i])return;bo[i]=hu;pt();if(ce())return;STE.textContent='Ход ИИ...';setTimeout(aiM,300)});function rs(){bo=Array(9).fill('');ov=false;STE.textContent='Ваш ход';pt()}c.querySelector('#tR').onclick=rs;rs();gameCleanup=()=>{}}
function initMines(c){const W=9,H=9,MI=10;let g,re,fl,ov,wo;c.innerHTML=`<div class="game-topbar"><div class="game-score">Мины: <b id="mmF">0/${MI}</b></div><button class="game-restart" id="mmR">Заново</button></div><div style="display:grid;grid-template-columns:repeat(9,36px);gap:2px;background:var(--surface-2);padding:7px;border-radius:13px" id="mmG"></div><div class="game-status" id="mmS"></div>`;const G=c.querySelector('#mmG'),SE=c.querySelector('#mmS'),FE=c.querySelector('#mmF');function eg(){return Array.from({length:H},()=>Array(W).fill(0))}function pm(sx,sy){let p=0;while(p<MI){const x=Math.floor(Math.random()*W),y=Math.floor(Math.random()*H);if(g[y][x]===-1)continue;if(Math.abs(x-sx)<=1&&Math.abs(y-sy)<=1)continue;g[y][x]=-1;p++}for(let y=0;y<H;y++)for(let x=0;x<W;x++){if(g[y][x]===-1)continue;let n=0;for(let dy=-1;dy<=1;dy++)for(let dx=-1;dx<=1;dx++){const ny=y+dy,nx=x+dx;if(ny>=0&&ny<H&&nx>=0&&nx<W&&g[ny][nx]===-1)n++}g[y][x]=n}}function rv(x,y){if(ov||wo||re[y][x]||fl[y][x])return;re[y][x]=true;if(g[y][x]===-1){ov=true;pt();SE.textContent='Взрыв!';return}if(g[y][x]===0){for(let dy=-1;dy<=1;dy++)for(let dx=-1;dx<=1;dx++){const ny=y+dy,nx=x+dx;if(ny>=0&&ny<H&&nx>=0&&nx<W&&!re[ny][nx]&&!fl[ny][nx])rv(nx,ny)}}pt()}function pt(){G.innerHTML=g.map((row,y)=>row.map((v,x)=>{if(!re[y][x]){const f=fl[y][x];return`<div data-mx="${x}" data-my="${y}" style="width:36px;height:36px;border-radius:6px;background:var(--surface-3);border:1px solid var(--border);display:flex;align-items:center;justify-content:center;font-size:14px;cursor:pointer">${f?'🚩':''}</div>`}if(v===-1)return`<div style="width:36px;height:36px;border-radius:6px;background:var(--red);display:flex;align-items:center;justify-content:center">💥</div>`;return`<div style="width:36px;height:36px;border-radius:6px;background:var(--surface);display:flex;align-items:center;justify-content:center;font-weight:800;font-size:14px;color:${v===1?'#3b8bff':v===2?'#22a355':v===3?'#ff3b30':'var(--muted)'}">${v||''}</div>`}).join('')).join('');const fls=fl.flat().filter(Boolean).length;FE.textContent=`${fls}/${MI}`}G.addEventListener('contextmenu',e=>{e.preventDefault();const el=e.target.closest('[data-mx]');if(!el||ov||wo)return;const x=+el.dataset.mx,y=+el.dataset.my;if(re[y][x])return;fl[y][x]=!fl[y][x];pt()});G.addEventListener('click',e=>{const el=e.target.closest('[data-mx]');if(!el||ov||wo)return;const x=+el.dataset.mx,y=+el.dataset.my;if(fl[y][x])return;if(!re.flat().some(Boolean)&&!ov){pm(x,y)}rv(x,y)});function rs(){g=eg();re=Array.from({length:H},()=>Array(W).fill(false));fl=Array.from({length:H},()=>Array(W).fill(false));ov=false;wo=false;SE.textContent='Кликните';pt()}c.querySelector('#mmR').onclick=rs;rs();gameCleanup=()=>{}}
function initTetris(c){const CO=10,RO=20,SZ=22;c.innerHTML=`<div class="game-topbar"><div class="game-score">Очки: <b id="ttS">0</b></div><button class="game-restart" id="ttR">Заново</button></div><canvas id="ttC" width="${CO*SZ}" height="${RO*SZ}" style="background:#000;border-radius:10px"></canvas><div class="game-status" id="ttSt"></div>`;const cv=c.querySelector('#ttC'),cx=cv.getContext('2d'),SE=c.querySelector('#ttS'),STE=c.querySelector('#ttSt');const SH=[[[1,1,1,1]],[[1,1],[1,1]],[[0,1,0],[1,1,1]],[[1,0,0],[1,1,1]],[[0,0,1],[1,1,1]],[[0,1,1],[1,1,0]],[[1,1,0],[0,1,1]]];let bo,cu,cuX,cuY,ti,ov,sc;function nb(){return Array.from({length:RO},()=>Array(CO).fill(0))}function sp(){cu=SH[Math.floor(Math.random()*SH.length)].map(r=>r.slice());cuX=Math.floor((CO-cu[0].length)/2);cuY=0;if(cl(cu,cuX,cuY)){ov=true;STE.textContent='Игра окончена';if(ti)clearInterval(ti)}}function cl(s,ox,oy){for(let y=0;y<s.length;y++)for(let x=0;x<s[y].length;x++){if(!s[y][x])continue;const nx=ox+x,ny=oy+y;if(nx<0||nx>=CO||ny>=RO)return true;if(ny>=0&&bo[ny][nx])return true}return false}function me(){cu.forEach((row,y)=>row.forEach((v,x)=>{if(v)bo[cuY+y][cuX+x]=1}))}function rt(){const r=cu[0].map((_,i)=>cu.map(row=>row[i]).reverse());if(!cl(r,cuX,cuY))cu=r}function cll(){let l=0;for(let y=RO-1;y>=0;y--){if(bo[y].every(v=>v)){bo.splice(y,1);bo.unshift(Array(CO).fill(0));l++;y++}}if(l){sc+=[0,100,300,500,800][l]||0;SE.textContent=sc}}function tk(){if(ov)return;if(!cl(cu,cuX,cuY+1)){cuY++}else{me();cll();sp()}dr()}function dr(){cx.fillStyle='#000';cx.fillRect(0,0,cv.width,cv.height);for(let y=0;y<RO;y++)for(let x=0;x<CO;x++){if(bo[y][x]){cx.fillStyle='#ff3b30';cx.fillRect(x*SZ+1,y*SZ+1,SZ-2,SZ-2)}}if(cu){cx.fillStyle='#fff';cu.forEach((row,y)=>row.forEach((v,x)=>{if(v)cx.fillRect((cuX+x)*SZ+1,(cuY+y)*SZ+1,SZ-2,SZ-2)}))}}const kh=e=>{if(ov)return;if(e.key==='ArrowLeft'){if(!cl(cu,cuX-1,cuY))cuX--;e.preventDefault()}else if(e.key==='ArrowRight'){if(!cl(cu,cuX+1,cuY))cuX++;e.preventDefault()}else if(e.key==='ArrowDown'){if(!cl(cu,cuX,cuY+1)){cuY++;sc+=1;SE.textContent=sc}e.preventDefault()}else if(e.key==='ArrowUp'){rt();e.preventDefault()}else if(e.key===' '){while(!cl(cu,cuX,cuY+1))cuY++;e.preventDefault()}dr()};window.addEventListener('keydown',kh);function rs(){bo=nb();cu=null;ov=false;sc=0;SE.textContent=0;STE.textContent='';sp();dr();if(ti)clearInterval(ti);ti=setInterval(tk,500)}c.querySelector('#ttR').onclick=rs;rs();gameCleanup=()=>{window.removeEventListener('keydown',kh);if(ti)clearInterval(ti)}}
function initBreakout(c){c.innerHTML=`<div class="game-topbar"><div class="game-score">Очки: <b id="bbS">0</b> · Жизни: <b id="bbL">3</b></div><button class="game-restart" id="bbR">Заново</button></div><canvas id="bbC" width="480" height="400" style="background:#000;border-radius:10px"></canvas><div class="game-status" id="bbSt"></div>`;const cv=c.querySelector('#bbC'),cx=cv.getContext('2d'),SE=c.querySelector('#bbS'),LE=c.querySelector('#bbL'),STE=c.querySelector('#bbSt'),W=cv.width,H=cv.height;let pa,ba,br,sc,li,pl,rf,ke={};function mb(){const a=[];for(let r=0;r<5;r++)for(let cc=0;cc<8;cc++)a.push({x:8+cc*56,y:8+r*24,w:52,h:18,alive:true,row:r});return a}function rs(){pa={x:W/2-40,y:H-20,w:80,h:12,speed:7};ba={x:W/2,y:H-40,r:7,vx:3.5,vy:-3.5};br=mb();sc=0;li=3;pl=true;SE.textContent=0;LE.textContent=3;STE.textContent='';if(rf)cancelAnimationFrame(rf);lo()}function dr(){cx.fillStyle='#000';cx.fillRect(0,0,W,H);const cl=['#ff3b30','#f97316','#ffcc00','#28a745','#007aff'];br.forEach(b=>{if(!b.alive)return;cx.fillStyle=cl[b.row%cl.length];cx.fillRect(b.x,b.y,b.w,b.h)});cx.fillStyle='#fff';cx.fillRect(pa.x,pa.y,pa.w,pa.h);cx.beginPath();cx.arc(ba.x,ba.y,ba.r,0,Math.PI*2);cx.fillStyle='#ff3b30';cx.fill()}function up(){if(!pl)return;if(ke.left)pa.x=Math.max(0,pa.x-pa.speed);if(ke.right)pa.x=Math.min(W-pa.w,pa.x+pa.speed);ba.x+=ba.vx;ba.y+=ba.vy;if(ba.x-ba.r<0||ba.x+ba.r>W)ba.vx*=-1;if(ba.y-ba.r<0)ba.vy*=-1;if(ba.y-ba.r>H){li--;LE.textContent=li;if(li<=0){pl=false;STE.textContent='Игра окончена'}else ba={x:W/2,y:H-40,r:7,vx:3.5,vy:-3.5}}if(ba.y+ba.r>pa.y&&ba.y-ba.r<pa.y+pa.h&&ba.x>pa.x&&ba.x<pa.x+pa.w){const hit=(ba.x-(pa.x+pa.w/2))/(pa.w/2);ba.vx=hit*6;ba.vy=-Math.abs(ba.vy)}br.forEach(b=>{if(!b.alive)return;if(ba.x+ba.r>b.x&&ba.x-ba.r<b.x+b.w&&ba.y+ba.r>b.y&&ba.y-ba.r<b.y+b.h){b.alive=false;ba.vy*=-1;sc+=10;SE.textContent=sc}});if(br.every(b=>!b.alive)){pl=false;STE.textContent='Победа!'}}function lo(){if(!pl){dr();return}up();dr();rf=requestAnimationFrame(lo)}const mm=e=>{const r=cv.getBoundingClientRect();pa.x=Math.max(0,Math.min(W-pa.w,(e.clientX-r.left)*(W/r.width)-pa.w/2))};const kd=e=>{if(e.key==='ArrowLeft')ke.left=true;if(e.key==='ArrowRight')ke.right=true};const ku=e=>{if(e.key==='ArrowLeft')ke.left=false;if(e.key==='ArrowRight')ke.right=false};cv.addEventListener('mousemove',mm);window.addEventListener('keydown',kd);window.addEventListener('keyup',ku);c.querySelector('#bbR').onclick=rs;rs();gameCleanup=()=>{if(rf)cancelAnimationFrame(rf);cv.removeEventListener('mousemove',mm);window.removeEventListener('keydown',kd);window.removeEventListener('keyup',ku)}}
function initReaction(c){let be=null,at=0;c.innerHTML=`<div class="game-topbar"><div class="game-score">Лучший: <b id="reB">—</b></div><button class="game-restart" id="reR">Заново</button></div><button id="reBtn" style="width:280px;height:220px;border-radius:22px;background:#141414;border:2px solid #242424;color:#fff;font-size:21px;font-weight:800;cursor:pointer">Нажмите для старта</button><div class="game-status" id="reS"></div>`;const btn=c.querySelector('#reBtn'),BE=c.querySelector('#reB'),SE=c.querySelector('#reS');let ph='idle',t0=0,to=null;function sw(){ph='wait';btn.style.background='#c43028';btn.textContent='Ждите...';const d=1500+Math.random()*3000;to=setTimeout(()=>{ph='go';btn.style.background='#22a355';btn.textContent='ЖМИ!';t0=performance.now()},d)}btn.onclick=()=>{if(ph==='idle'){sw();return}if(ph==='wait'){clearTimeout(to);ph='idle';btn.style.background='#141414';btn.textContent='Слишком рано!';return}if(ph==='go'){const t=Math.round(performance.now()-t0);at++;if(!be||t<be)be=t;BE.textContent=be+' мс';ph='idle';btn.style.background='#141414';btn.textContent=t+' мс'}};c.querySelector('#reR').onclick=()=>{clearTimeout(to);ph='idle';be=null;BE.textContent='—';btn.style.background='#141414';btn.textContent='Нажмите для старта'};gameCleanup=()=>{if(to)clearTimeout(to)}}
function initGuess(c){let se,tr,ov;c.innerHTML=`<div class="game-topbar"><div class="game-score">Попыток: <b id="guT">0</b></div><button class="game-restart" id="guR">Заново</button></div><div style="display:flex;gap:9px"><input id="guI" type="number" min="1" max="100" placeholder="1–100" style="width:130px;height:48px;padding:0 14px;border-radius:11px;border:1px solid #242424;background:#141414;color:#fff;font-size:19px;font-weight:700;text-align:center;outline:none"><button class="btn-primary" id="guG">Проверить</button></div><div class="game-status" id="guS"></div>`;const inp=c.querySelector('#guI'),go=c.querySelector('#guG'),SE=c.querySelector('#guS'),TE=c.querySelector('#guT');function ck(){if(ov)return;const v=parseInt(inp.value,10);if(isNaN(v)||v<1||v>100){SE.textContent='Введите 1–100';return}tr++;TE.textContent=tr;if(v===se){ov=true;SE.textContent=`Угадали за ${tr}!`}else{SE.textContent=v<se?'Больше':'Меньше'}inp.value='';inp.focus()}go.onclick=ck;inp.addEventListener('keydown',e=>{if(e.key==='Enter')ck()});function rs(){se=1+Math.floor(Math.random()*100);tr=0;ov=false;TE.textContent=0;SE.textContent='Угадайте 1–100';inp.value='';inp.focus()}c.querySelector('#guR').onclick=rs;rs();gameCleanup=()=>{}}

/* === ПЛАТЕЖИ === */
const PAYMENT_METHODS=[{id:'tbank',name:'Т-Банк',sub:'Карта, СБП',logo:'T',cls:'tbank'},{id:'sber',name:'Сбербанк',sub:'Карта',logo:'С',cls:'sber'},{id:'sbp',name:'СБП',sub:'Быстрые платежи',logo:'СБП',cls:'sbp'},{id:'card',name:'Другая карта',sub:'Visa · MC · МИР',logo:'💳',cls:'card'}];
let pendingPayment=null;
function openPaymentModal(opts){pendingPayment=opts;document.getElementById('payModalTitle').textContent=opts.type==='vip'?'💳 Оплата VIP':'💳 Оплата';renderPaymentMethods();document.getElementById('paymentModal').hidden=false}
function closePaymentModal(){document.getElementById('paymentModal').hidden=true;pendingPayment=null;try{render()}catch(e){}window.scrollTo({top:0,behavior:'smooth'});toast('↩️ Возврат в VK Visual')}
function renderPaymentMethods(){if(!pendingPayment)return;const body=document.getElementById('payBody');const opts=pendingPayment;body.innerHTML=`<div class="pay-amount-box"><div class="pay-amount-label">К оплате</div><div class="pay-amount-value">${opts.amount.toLocaleString('ru-RU')} ₽</div><div class="pay-amount-desc">${esc(opts.label)}</div></div><div class="pay-summary"><div class="pay-summary-row"><span>Товар</span><span>${esc(opts.label)}</span></div><div class="pay-summary-row total"><span>Итого</span><span>${opts.amount.toLocaleString('ru-RU')} ₽</span></div></div><div class="pay-methods">${PAYMENT_METHODS.map(m=>`<div class="pay-method" data-pay-method="${m.id}"><div class="pay-method-logo ${m.cls}">${m.logo}</div><div class="pay-method-info"><div class="pay-method-name">${esc(m.name)}</div><div class="pay-method-sub">${esc(m.sub)}</div></div><div class="pay-method-arrow">→</div></div>`).join('')}</div><div class="pay-demo-warning">🔧 <b>Демо:</b> реальная оплата не происходит.</div>`}
function processPayment(methodId){if(!pendingPayment)return;const method=PAYMENT_METHODS.find(m=>m.id===methodId);const body=document.getElementById('payBody');const opts=pendingPayment;body.innerHTML=`<div class="pay-processing"><div class="pay-spinner"></div><div style="font-size:16px;font-weight:700">Обработка через ${esc(method.name)}...</div></div>`;setTimeout(()=>{if(opts.type==='vip'){grantVIP(opts.days);saveCurrentAccountToDb()}body.innerHTML=`<div class="pay-success"><div class="pay-success-icon">✅</div><div class="pay-success-title">Оплата прошла успешно</div><div class="pay-success-sub">${opts.amount.toLocaleString('ru-RU')} ₽ списано</div><button class="btn-primary" id="payDoneBtn" style="margin-top:14px;padding:12px 40px">Готово</button></div>`;document.getElementById('payDoneBtn').onclick=()=>closePaymentModal();setTimeout(()=>{if(!document.getElementById('paymentModal').hidden)closePaymentModal()},4000)},1800)}

function activateCodeFromInput(){const inp=document.getElementById('codeInput');if(!inp)return;const code=inp.value.trim().toUpperCase();const resultEl=document.getElementById('codeResult');if(!code){if(resultEl){resultEl.textContent='Введите код';resultEl.className='code-result err'}return}if(state.usedCodes.includes(code)){if(resultEl){resultEl.textContent='Уже использован';resultEl.className='code-result err'}return}const promo=PROMO_CODES[code];if(!promo){if(resultEl){resultEl.textContent='Неверный код';resultEl.className='code-result err'}return}const r=promo.reward;if(r.type==='bkv'){state.coins+=r.amount;persistCoins()}else if(r.type==='voices'){state.voices+=r.amount;persistVoices()}else if(r.type==='vip'){grantVIP(r.days||30)}else if(r.type==='random-pack'){const av=STICKER_PACKS.filter(p=>!state.purchasedPacks.includes(p.id));if(av.length){const pack=av[Math.floor(Math.random()*av.length)];state.purchasedPacks.push(pack.id);persistPacks()}}else if(r.type==='all-packs'){state.purchasedPacks=STICKER_PACKS.map(p=>p.id);persistPacks()}state.usedCodes.push(code);persistCodes();saveCurrentAccountToDb();if(resultEl){resultEl.textContent=promo.desc+' — получено!';resultEl.className='code-result ok'}toast('✅ '+promo.desc);setTimeout(()=>render(),800)}

function setView(v){if(state.view==='games' && v!=='games'){if(gameCleanup){try{gameCleanup()}catch(e){}gameCleanup=null}state.currentGame=null}state.view=v;window.scrollTo(0,0);render();const m=document.getElementById('main');if(m){m.classList.remove('fadeIn');void m.offsetWidth;m.classList.add('fadeIn')}}

const EMOJI_CLICK_MAP={hearts:'❤️',stars:'⭐',flowers:'🌸',leaves:'🍂',sparkles:'✨',crown:'👑',money:'💰',diamonds:'💎',fire:'🔥',ice:'❄️',bubbles:'⚪',rose:'🌹',cherry:'🌸',doll:'🎀',glitter:'✨',pinkheart:'💖',unicorn:'🦄',butterfly:'🦋',pinksparkle:'💕'};
document.addEventListener('pointerdown',function(e){
  const type=state.clickEffect||'none';
  if(type==='none'||!type)return;
  const tag=e.target.tagName;
  if(tag==='INPUT'||tag==='TEXTAREA'||tag==='SELECT')return;
  document.querySelectorAll('.click-ripple, .emoji-click').forEach(function(el){el.remove()});
  const emoji=EMOJI_CLICK_MAP[type];
  if(emoji){const el=document.createElement('div');el.className='emoji-click';el.textContent=emoji;el.style.left=e.clientX+'px';el.style.top=e.clientY+'px';document.body.appendChild(el);setTimeout(function(){el.remove()},1000);return}
  const el=document.createElement('div');el.className='click-ripple '+type;el.style.left=e.clientX+'px';el.style.top=e.clientY+'px';el.style.width='40px';el.style.height='40px';document.body.appendChild(el);setTimeout(function(){el.remove()},750);
});
window.setClickEffect=function(id){state.clickEffect=id;try{localStorage.setItem('vk_click_effect',id)}catch(e){}toast(id==='none'?'🚫 Эффект отключён':'✨ Эффект изменён');try{render()}catch(e){}};

function restoreVIP(){const now=Date.now();let maxVip=Number(state.me.vipUntil)||0;try{const p=JSON.parse(localStorage.getItem('vk_profile')||'{}');if(p.vipUntil&&Number(p.vipUntil)>maxVip)maxVip=Number(p.vipUntil)}catch(e){}const lsv=Number(localStorage.getItem('vk_vip_until'))||0;if(lsv>maxVip)maxVip=lsv;try{const bk=JSON.parse(localStorage.getItem('vk_vip_backup')||'null');if(bk&&bk.until&&Number(bk.until)>maxVip)maxVip=Number(bk.until)}catch(e){}const curId=getAccountId();if(curId){const db=getAccountsDb();if(db[curId]?.data?.me?.vipUntil&&Number(db[curId].data.me.vipUntil)>maxVip)maxVip=Number(db[curId].data.me.vipUntil)}try{const db=getAccountsDb();Object.keys(db).forEach(id=>{const v=Number(db[id]?.data?.me?.vipUntil)||0;if(v>maxVip)maxVip=v})}catch(e){}if(maxVip>now){state.me.vipUntil=maxVip;persistProfile();saveCurrentAccountToDb();try{localStorage.setItem('vk_vip_until',String(maxVip))}catch(e){}try{localStorage.setItem('vk_vip_backup',JSON.stringify({until:maxVip,account:curId,time:now}))}catch(e){}const daysLeft=Math.ceil((maxVip-now)/DAY_MS);toast('👑 VIP восстановлен! Осталось '+daysLeft+' дн.');render();return true}else{toast('VIP не найден');return false}}
function restoreAdmin(){if(!state.me||!state.me.name){toast('❌ Сначала войдите');return false}state.me.isAdmin=true;persistProfile();saveCurrentAccountToDb();try{localStorage.setItem('vk_owner','1')}catch(e){}try{localStorage.setItem('vk_owner_id',getAccountId()||'')}catch(e){}toast('👑 Admin восстановлен!');render();return true}
function removeAdmin(){state.me.isAdmin=false;persistProfile();saveCurrentAccountToDb();try{localStorage.removeItem('vk_owner')}catch(e){}toast('Admin снят');render()}

document.addEventListener('click',e=>{
  const clickBtn=e.target.closest('[data-set-click]');if(clickBtn){window.setClickEffect(clickBtn.dataset.setClick);return}
  const avStyle=e.target.closest('[data-set-avatar-style]');if(avStyle){pendingAvatarStyle=avStyle.dataset.setAvatarStyle;renderAvatarStylePicker();renderAvatarPreview();return}
  const covStyle=e.target.closest('[data-set-cover-style]');if(covStyle){pendingCoverStyle=covStyle.dataset.setCoverStyle;renderCoverStylePicker();return}
  const roleBtn=e.target.closest('[data-set-role]');if(roleBtn){pendingRole=roleBtn.dataset.setRole||null;renderRolePicker();return}
  const sw=e.target.closest('[data-switch-account]');if(sw){switchAccount(sw.dataset.switchAccount);return}
  const delAcc=e.target.closest('[data-delete-account]');if(delAcc){deleteAccountById(delAcc.dataset.deleteAccount);return}
  const themeBtn=e.target.closest('[data-theme]');if(themeBtn){state.theme=themeBtn.dataset.theme;try{localStorage.setItem('vk_theme',state.theme)}catch(e){}applyTheme();render();return}
  const genderBtn=e.target.closest('[data-gender]');if(genderBtn){state.me.gender=genderBtn.dataset.gender;persistProfile();saveCurrentAccountToDb();document.getElementById('genderModal').hidden=true;render();return}
  if(e.target.closest('[data-open-sticker-picker]')){openStickerPicker();return}
  const pickS=e.target.closest('[data-pick-sticker]');if(pickS){pickSticker(pickS.dataset.pickSticker);return}
  const copyS=e.target.closest('[data-copy-sticker]');if(copyS){const s=copyS.dataset.copySticker;if(navigator.clipboard)navigator.clipboard.writeText(s).then(()=>toast('Стикер скопирован')).catch(()=>toast('Стикер: '+s));return}
  const packBtn=e.target.closest('[data-buy-pack]');if(packBtn){buyStickerPack(packBtn.dataset.buyPack);return}
  const vu=e.target.closest('[data-view-user]');if(vu){state.viewingAccount=vu.dataset.viewUser;setView('user-profile');return}
  const ft=e.target.closest('[data-friend-toggle]');if(ft){toggleFriend(ft.dataset.friendToggle);return}
  const mu=e.target.closest('[data-message-user]');if(mu){openChat(mu.dataset.messageUser);return}
  const viewEl=e.target.closest('[data-view]');if(viewEl){e.preventDefault();setView(viewEl.dataset.view);return}
  const buyVipBtn=e.target.closest('[data-buy-vip]');if(buyVipBtn&&!buyVipBtn.disabled){buyVIP(parseInt(buyVipBtn.dataset.buyVip,10)||30,buyVipBtn.dataset.currency||'coins');return}
  const pack=e.target.closest('[data-pack]');if(pack){buyCoinPack(pack.dataset.pack);return}
  const play=e.target.closest('[data-play]');if(play){playTrack(+play.dataset.play);return}
  const game=e.target.closest('[data-game]');if(game){state.currentGame=game.dataset.game;render();return}
  if(e.target.closest('[data-game-exit]')){exitGame();return}
  const gd=e.target.closest('[data-gallery-del]');if(gd){e.stopPropagation();state.gallery.splice(+gd.dataset.galleryDel,1);persistGallery();saveCurrentAccountToDb();render();return}
  const g=e.target.closest('[data-gallery]');if(g){openGalleryViewer(+g.dataset.gallery);return}
  const comm=e.target.closest('[data-community]');if(comm){const i=+comm.dataset.community;communities[i].joined=!communities[i].joined;render();return}
  const act=e.target.closest('[data-act]');if(act){handlePostAction(act);return}
},{passive:true});

/* === ФУНКЦИЯ ДРУГА === */
function toggleFriend(userId){if(!userId)return;if(state.friends.includes(userId)){state.friends=state.friends.filter(f=>f!==userId);toast('Удалён из друзей')}else{state.friends.push(userId);toast('✅ Добавлен в друзья')}persistFriends();saveCurrentAccountToDb();render()}

/* === ХЕДЕР === */
const searchInput=document.getElementById('searchInput');
if(searchInput)searchInput.addEventListener('keydown',e=>{if(e.key==='Enter'){state.musicQuery=searchInput.value.trim();setView('music')}});
let logoClicks=0,logoTimer=null;
const logoBtn=document.getElementById('logoBtn');
if(logoBtn)logoBtn.addEventListener('click',()=>{logoClicks++;clearTimeout(logoTimer);logoTimer=setTimeout(()=>{logoClicks=0},600);if(logoClicks>=3){logoClicks=0;openDevPassword()}});
document.addEventListener('keydown',e=>{if(e.key==='z'||e.key==='Z'||e.key==='я'||e.key==='Я'){const tag=(document.activeElement&&document.activeElement.tagName)||'';if(tag==='INPUT'||tag==='TEXTAREA')return;openDevPassword()}});

/* === РЕГИСТРАЦИЯ === */
const REG_DEMO_CODE='1234';let regGender=null;
function showRegistration(){const m=document.getElementById('registrationModal');if(m)m.hidden=false}
function hideRegistration(){const m=document.getElementById('registrationModal');if(m)m.hidden=true}
function switchRegTab(tab){document.querySelectorAll('.reg-tab').forEach(b=>b.classList.toggle('active',b.dataset.regTab===tab));document.getElementById('regPhoneSection').hidden=tab!=='phone';document.getElementById('regGmailSection').hidden=tab!=='gmail'}
function showRegNameStep(){document.getElementById('regPhoneSection').hidden=true;document.getElementById('regGmailSection').hidden=true;document.getElementById('regNameStep').hidden=false}
function regFinish(){
  const name=document.getElementById('regName').value.trim();
  if(!name){toast('Введите имя');return}
  if(!regGender){toast('Выберите пол');return}
  const phone=document.getElementById('regPhone').value.trim();
  const gmail=document.getElementById('regGmail').value.trim();
  const accountId=phone||gmail||'';
  const db=getAccountsDb();
  const isFirst=Object.keys(db).length===0;
  state.me={name,initials:deriveInitials(name),status:'',city:'',about:'',role:null,coverStyle:'none',avatarStyle:'none',isAdmin:isFirst,vipUntil:0,gender:regGender,avatarPhoto:null,phone:accountId,email:gmail||'',accountId:null};
  if(isFirst){try{localStorage.setItem('vk_owner','1')}catch(e){}try{localStorage.setItem('vk_owner_id',accountId)}catch(e){}}
  state.coins=0;state.voices=0;state.purchased=[];state.purchasedPacks=[];state.usedCodes=[];state.gallery=[];state.media=[];state.friends=[];state.messages={};
  persistProfile();persistCoins();persistVoices();persistPurchased();persistPacks();persistCodes();persistGallery();persistMedia();persistFriends();persistMessages();
  saveCurrentAccountToDb();
  localStorage.setItem('vk_registered','1');
  hideRegistration();document.getElementById('genderModal').hidden=true;render();
  toast('🎉 Добро пожаловать, '+name+'!');
}
function initRegistration(){
  document.querySelectorAll('.reg-tab').forEach(b=>b.onclick=()=>switchRegTab(b.dataset.regTab));
  document.getElementById('regPhoneSend').onclick=()=>{const p=document.getElementById('regPhone').value.trim();if(p.replace(/\D/g,'').length<10){toast('Введите номер');return}document.getElementById('regPhoneCodeStep').hidden=false;document.getElementById('regPhoneCode').focus();toast('📩 Демо-код: '+REG_DEMO_CODE)};
  document.getElementById('regPhoneVerify').onclick=()=>{if(document.getElementById('regPhoneCode').value.trim()!==REG_DEMO_CODE){toast('❌ Неверный код');return}showRegNameStep()};
  document.getElementById('regGmailSend').onclick=()=>{const g=document.getElementById('regGmail').value.trim();if(!/^[^\s@]+@[^\s@]+\.[^\s@]+$/.test(g)){toast('Введите Gmail');return}document.getElementById('regGmailCodeStep').hidden=false;document.getElementById('regGmailCode').focus();toast('📩 Демо-код: '+REG_DEMO_CODE)};
  document.getElementById('regGmailVerify').onclick=()=>{if(document.getElementById('regGmailCode').value.trim()!==REG_DEMO_CODE){toast('❌ Неверный код');return}showRegNameStep()};
  document.querySelectorAll('[data-reg-gender]').forEach(b=>b.onclick=()=>{regGender=b.dataset.regGender;document.querySelectorAll('[data-reg-gender]').forEach(x=>{x.style.borderColor='var(--border)';x.style.background='var(--surface-2)'});b.style.borderColor='var(--red)';b.style.background='var(--red-soft)'});
  document.getElementById('regFinish').onclick=regFinish;
}

function initAuth(){
  const isRegistered=localStorage.getItem('vk_registered')==='1';
  const lastId=localStorage.getItem('vk_current_account_id');
  if(lastId){try{const db=getAccountsDb();if(db[lastId]&&db[lastId].data){if(!state.me.name||!(state.me.phone||state.me.email||state.me.accountId)){loadAccountFromDb(lastId)}}}catch(e){console.error('load',e)}}
  const hasValidAccount=!!(state.me&&state.me.name&&(state.me.phone||state.me.email||state.me.accountId));
  if(isRegistered&&hasValidAccount)return;
  showRegistration();
}

/* === DEV === */
let devPassword='admin';try{const dp=localStorage.getItem('vk_dev_pw');if(dp)devPassword=dp}catch(e){}
let devUnlocked=false,devDisabled=false;
function openDevPassword(){if(devDisabled)return;if(devUnlocked){openDevPanel();return}document.getElementById('devPassError').style.display='none';document.getElementById('devPassInput').value='';document.getElementById('devPassModal').hidden=false;setTimeout(()=>document.getElementById('devPassInput').focus(),50)}
function checkDevPassword(){const v=document.getElementById('devPassInput').value;if(v===devPassword){document.getElementById('devPassModal').hidden=true;devUnlocked=true;if(state.me&&state.me.name){state.me.isAdmin=true;persistProfile();saveCurrentAccountToDb();try{localStorage.setItem('vk_owner','1')}catch(e){}try{localStorage.setItem('vk_owner_id',getAccountId()||'')}catch(e){}}openDevPanel();render()}else{document.getElementById('devPassError').style.display='block'}}
function updateDevPanel(){document.getElementById('devBalance').textContent=state.coins;document.getElementById('devVoices').textContent=state.voices;document.getElementById('devVIPStatus').textContent=isVIP()?`Активен · ${vipDaysLeft()} дн.`:'Нет'}
function openDevPanel(){devUnlocked=true;updateDevPanel();document.getElementById('devPanelBackdrop').hidden=false}
function closeDevPanel(){document.getElementById('devPanelBackdrop').hidden=true}

/* === ОБРАБОТЧИКИ === */
document.getElementById('avatarPhotoInput').addEventListener('change',e=>{const file=e.target.files[0];if(!file)return;if(!file.type.startsWith('image/')){toast('⚠️ Выберите изображение');e.target.value='';return}if(file.size>2*1024*1024){toast('⚠️ Фото > 2 MB');e.target.value='';return}const reader=new FileReader();reader.onload=()=>{pendingAvatarPhoto=reader.result;renderAvatarPreview();toast('📸 Фото прикреплено')};reader.readAsDataURL(file)});
document.getElementById('avatarPhotoRemove').addEventListener('click',()=>{pendingAvatarPhoto=null;document.getElementById('avatarPhotoInput').value='';renderAvatarPreview();toast('Фото убрано')});
document.getElementById('fName').addEventListener('input',renderAvatarPreview);
document.getElementById('modalClose').onclick=closeProfileModal;
document.getElementById('modalCancel').onclick=closeProfileModal;
document.getElementById('modalSave').onclick=()=>{const oldId=getAccountId();state.me.name=document.getElementById('fName').value.trim()||'Без имени';state.me.status=document.getElementById('fStatus').value.trim();state.me.city=document.getElementById('fCity').value.trim();state.me.phone=document.getElementById('fPhone').value.trim();state.me.email=document.getElementById('fEmail').value.trim();state.me.about=document.getElementById('fAbout').value.trim();state.me.role=pendingRole;state.me.avatarPhoto=pendingAvatarPhoto;state.me.avatarStyle=pendingAvatarStyle;state.me.coverStyle=pendingCoverStyle;state.me.initials=deriveInitials(state.me.name);posts.forEach(p=>{if(p.mine)p.author=state.me.name});persistProfile();persistPosts();const newId=getAccountId();if(oldId&&newId&&oldId!==newId){const db=getAccountsDb();delete db[oldId];saveAccountsDb(db)}saveCurrentAccountToDb();closeProfileModal();render();toast('Сохранено')};
document.getElementById('stickerPickerClose').onclick=()=>{document.getElementById('stickerPickerModal').hidden=true};
document.getElementById('stickerPickerModal').addEventListener('click',e=>{if(e.target.id==='stickerPickerModal')e.target.hidden=true});
document.getElementById('accountsClose').onclick=closeAccountsModal;
document.getElementById('accountsModal').addEventListener('click',e=>{if(e.target.id==='accountsModal')closeAccountsModal()});
document.getElementById('newAccClose').onclick=closeNewAccountModal;
document.getElementById('newAccCancel').onclick=closeNewAccountModal;
document.getElementById('newAccCreate').onclick=createNewAccountSubmit;
document.getElementById('newAccountModal').addEventListener('click',e=>{if(e.target.id==='newAccountModal')closeNewAccountModal()});
document.querySelectorAll('[data-newacc-gender]').forEach(b=>b.onclick=()=>{newAccGender=b.dataset.newaccGender;document.querySelectorAll('[data-newacc-gender]').forEach(x=>{x.style.borderColor='var(--border)';x.style.background='var(--surface-2)'});b.style.borderColor='var(--red)';b.style.background='var(--red-soft)'});
document.getElementById('ideaClose').onclick=closeIdeaModal;
document.getElementById('ideaCancel').onclick=closeIdeaModal;
document.getElementById('ideaSend').onclick=sendIdea;
document.getElementById('ideaText').addEventListener('input',e=>{document.getElementById('ideaCounter').textContent=e.target.value.length+'/500'});
document.getElementById('payClose').onclick=closePaymentModal;
document.getElementById('payBackBtn').onclick=closePaymentModal;
document.getElementById('paymentModal').addEventListener('click',e=>{if(e.target.id==='paymentModal')closePaymentModal();const m=e.target.closest('[data-pay-method]');if(m)processPayment(m.dataset.payMethod)});
document.getElementById('notifAllow').onclick=async()=>{document.getElementById('notifPermissionModal').hidden=true;try{if('Notification' in window){const perm=await Notification.requestPermission();localStorage.setItem('vk_notif_permission',perm)}}catch(e){}try{ensureAudio()}catch(e){}toast('🔔 Уведомления включены')};
document.getElementById('notifDeny').onclick=()=>{document.getElementById('notifPermissionModal').hidden=true;localStorage.setItem('vk_notif_permission','denied');toast('Уведомления отключены')};

document.getElementById('chatClose').onclick=closeChat;
document.getElementById('chatSend').onclick=sendChatMessage;
document.getElementById('chatInput').addEventListener('keydown',e=>{if(e.key==='Enter')sendChatMessage()});
document.getElementById('chatModal').addEventListener('click',e=>{if(e.target.id==='chatModal')closeChat()});
document.getElementById('chatEmojiBtn').onclick=()=>{const panel=document.getElementById('chatEmojiPanel');if(panel.style.display==='flex'){panel.style.display='none';return}const emojis=['😀','😂','🥰','😍','😎','🤩','🥳','😭','👍','🔥','❤️','💖','🌹','🌸','🎀','🦋','✨','💕','💫','🌟','🎉','🎊','😘','🤗','😊','🙂','😉','😇','🥺','😢','😡','🤬','💀','👻','🎃','🎁','🍕','🍔','🍩','🍰','☕','🍾','🥂','🎵','🎶','🎮','🏆','💎','👑','🦄','🌈'];panel.innerHTML=emojis.map(em=>`<button data-emoji="${em}" style="font-size:22px;padding:4px;background:transparent;border:none;cursor:pointer">${em}</button>`).join('');panel.style.display='flex';panel.querySelectorAll('[data-emoji]').forEach(btn=>{btn.onclick=(ev)=>{ev.stopPropagation();const inp=document.getElementById('chatInput');inp.value+=btn.dataset.emoji;inp.focus()}})};
document.getElementById('chatVoiceBtn').onclick=()=>{const btn=document.getElementById('chatVoiceBtn');if(btn.dataset.recording==='1'){stopVoiceRecording()}else{startVoiceRecording()}};
document.getElementById('gvClose').onclick=e=>{e.stopPropagation();document.getElementById('galleryViewer').hidden=true};
document.getElementById('galleryViewer').onclick=()=>{document.getElementById('galleryViewer').hidden=true};

document.getElementById('devToggleBtn').onclick=openDevPassword;
document.getElementById('devPassClose').onclick=()=>{document.getElementById('devPassModal').hidden=true};
document.getElementById('devPassCancel').onclick=()=>{document.getElementById('devPassModal').hidden=true};
document.getElementById('devPassOk').onclick=checkDevPassword;
document.getElementById('devPassInput').addEventListener('keydown',e=>{if(e.key==='Enter')checkDevPassword()});
document.getElementById('devClose').onclick=closeDevPanel;
document.querySelectorAll('[data-give]').forEach(b=>{b.onclick=()=>{state.coins+=parseInt(b.dataset.give,10)||0;persistCoins();saveCurrentAccountToDb();updateDevPanel();render();toast('BkV начислены')}});
document.querySelectorAll('[data-give-voice]').forEach(b=>{b.onclick=()=>{state.voices+=parseInt(b.dataset.giveVoice,10)||0;persistVoices();saveCurrentAccountToDb();updateDevPanel();render();toast('Голоса начислены')}});
document.querySelectorAll('[data-vip-give]').forEach(b=>{b.onclick=()=>{grantVIP(parseInt(b.dataset.vipGive,10)||30);saveCurrentAccountToDb();updateDevPanel();render();toast('👑 VIP выдан')}});
document.querySelectorAll('[data-set-gender]').forEach(b=>{b.onclick=()=>{state.me.gender=b.dataset.setGender;persistProfile();saveCurrentAccountToDb();render()}});
document.getElementById('devSetCoinsBtn').onclick=()=>{const v=parseInt(document.getElementById('devSetCoinsInput').value,10);if(isNaN(v)||v<0)return;state.coins=v;persistCoins();saveCurrentAccountToDb();updateDevPanel();render()};
document.getElementById('devSetVoicesBtn').onclick=()=>{const v=parseInt(document.getElementById('devSetVoicesInput').value,10);if(isNaN(v)||v<0)return;state.voices=v;persistVoices();saveCurrentAccountToDb();updateDevPanel();render()};
document.getElementById('devUnlockAllStickers').onclick=()=>{state.purchasedPacks=STICKER_PACKS.map(p=>p.id);persistPacks();saveCurrentAccountToDb();render()};
document.getElementById('devVIPRemove').onclick=()=>{state.me.vipUntil=0;persistProfile();saveCurrentAccountToDb();render()};
const dvr=document.getElementById('devVIPRestore');if(dvr)dvr.onclick=()=>{restoreVIP();updateDevPanel()};
const dag=document.getElementById('devAdminGive');if(dag)dag.onclick=()=>{restoreAdmin();updateDevPanel()};
const dar=document.getElementById('devAdminRemove');if(dar)dar.onclick=()=>{removeAdmin();updateDevPanel()};

/* === СНЯТЬ АДМИНКУ ПО ID === */
document.getElementById('devRemoveAdminById').onclick=()=>{
  const id=document.getElementById('devRemoveAdminId').value.trim();
  if(!id){toast('Введите ID');return}
  const db=getAccountsDb();
  let targetId=id;
  if(!db[targetId]){
    for(const k of Object.keys(db)){
      if((db[k].name||'').toUpperCase()===id.toUpperCase()){targetId=k;break}
    }
  }
  if(!db[targetId]){toast('❌ Аккаунт не найден');return}
  if(db[targetId].data?.me) db[targetId].data.me.isAdmin=false;
  saveAccountsDb(db);
  if(getAccountId()===targetId){state.me.isAdmin=false;persistProfile()}
  toast('✅ С админа снят: '+(db[targetId].name||targetId));
  document.getElementById('devRemoveAdminId').value='';
  render();
};

/* === БЫСТРОЕ СНЯТИЕ АДМИНКИ С M4AX1M ПРИ ЗАГРУЗКЕ === */
(function removeM4AX1MAdmin(){
  try{
    const db=getAccountsDb();
    let found=false;
    Object.keys(db).forEach(k=>{
      const acc=db[k];
      if(acc && acc.data && acc.data.me){
        const name=(acc.data.me.name||acc.name||'').toUpperCase();
        if(name==='M4AX1M' || k.toUpperCase()==='M4AX1M'){
          if(acc.data.me.isAdmin){
            acc.data.me.isAdmin=false;
            found=true;
          }
        }
      }
    });
    if(found) saveAccountsDb(db);
  }catch(e){console.error('[removeM4AX1M]',e)}
})();

document.getElementById('devBanBtn').onclick=()=>{state.banned=true;try{localStorage.setItem('vk_banned','1')}catch(e){}document.getElementById('bannedOverlay').hidden=false};
document.getElementById('devUnbanBtn').onclick=()=>{state.banned=false;try{localStorage.setItem('vk_banned','0')}catch(e){}document.getElementById('bannedOverlay').hidden=true};
document.getElementById('devResetAll').onclick=()=>{try{localStorage.clear()}catch(e){}location.reload()};
document.getElementById('regLoginAsAdmin').onclick=()=>{const v=prompt('Dev-пароль (по умолчанию: admin):');if(v===null)return;if(v===devPassword){const db=getAccountsDb();if(!db['v1lard_acc']){toast('❌ V1LARD не найден');return}localStorage.setItem('vk_registered','1');localStorage.setItem('vk_owner','1');localStorage.setItem('vk_owner_id','v1lard_acc');localStorage.setItem('vk_current_account_id','v1lard_acc');loadAccountFromDb('v1lard_acc');hideRegistration();document.getElementById('genderModal').hidden=true;render();toast('👑 Добро пожаловать, V1LARD!')}else{toast('❌ Неверный пароль')}};
document.getElementById('devLoginV1LARD').onclick=()=>{const db=getAccountsDb();if(!db['v1lard_acc']){toast('❌ V1LARD не найден');return}saveCurrentAccountToDb();localStorage.setItem('vk_registered','1');localStorage.setItem('vk_owner','1');localStorage.setItem('vk_owner_id','v1lard_acc');localStorage.setItem('vk_current_account_id','v1lard_acc');loadAccountFromDb('v1lard_acc');closeDevPanel();render();toast('👑 Вы вошли как V1LARD')};
document.getElementById('devLogout').onclick=()=>{saveCurrentAccountToDb();localStorage.removeItem('vk_current_account_id');localStorage.removeItem('vk_registered');localStorage.removeItem('vk_profile');state.me={name:'',initials:'??',status:'',city:'',phone:'',email:'',about:'',role:null,coverStyle:'none',avatarStyle:'none',isAdmin:false,vipUntil:0,gender:null,avatarPhoto:null,accountId:null};closeDevPanel();showRegistration();toast('👋 Вы вышли — зарегистрируйте новый аккаунт')};

document.getElementById('bannedUnbanBtn').onclick=()=>{if(state.me && state.me.isAdmin){state.banned=false;try{localStorage.setItem('vk_banned','0')}catch(e){}document.getElementById('bannedOverlay').hidden=true;toast('✅ Разбанен');try{render()}catch(e){}return}const v=prompt('Dev-пароль:');if(v===null)return;if(v===devPassword){state.banned=false;try{localStorage.setItem('vk_banned','0')}catch(e){}document.getElementById('bannedOverlay').hidden=true;toast('✅ Разбанен');try{render()}catch(e){}}else{toast('❌ Неверный пароль')}};
document.getElementById('bannedResetBtn').onclick=()=>{const v=prompt('Введите "СБРОС" для подтверждения:');if(v!=='СБРОС' && v!=='сброс'){toast('Отменено');return}try{localStorage.clear()}catch(e){}location.reload()};

document.getElementById('confirmDeleteCancel').onclick=closeDeleteModal;
document.getElementById('confirmDeleteModal').addEventListener('click',e=>{if(e.target.id==='confirmDeleteModal')closeDeleteModal()});
document.getElementById('confirmDeleteOk').onclick=confirmDeleteAccount;

/* === SEED V1LARD === */
(function ensureV1LARD(){
  try{
    const db=getAccountsDb();
    const v1lardId='v1lard_acc';
    if(!db[v1lardId]){
      const me={name:'V1LARD',initials:'V1',status:'Владелец VK Visual',city:'',phone:'',email:'',about:'Создатель VK Visual',role:'youtuber',coverStyle:'galaxy',avatarStyle:'neon',isAdmin:true,vipUntil:Date.now()+36500*24*60*60*1000,gender:'boy',avatarPhoto:null,accountId:v1lardId};
      db[v1lardId]={id:v1lardId,name:'V1LARD',phone:'',email:'',gender:'boy',password:'v1lard',data:{me,coins:99999,voices:99999,purchased:[],purchasedPacks:STICKER_PACKS.map(p=>p.id),usedCodes:[],gallery:[],media:[],posts:[],friends:[],messages:{}}};
      saveAccountsDb(db);
    }
  }catch(e){console.error('[seed]',e)}
  try{if(!state.view||state.view==='undefined')state.view='home'}catch(e){}
})();

/* === ИНИЦИАЛИЗАЦИЯ === */
try{applyTheme()}catch(e){}
if(state.banned)document.getElementById('bannedOverlay').hidden=false;
try{initRegistration()}catch(e){console.error('[initReg]',e)}
try{render()}catch(e){console.error('[initRender]',e)}
try{initAuth()}catch(e){console.error('[initAuth]',e)}
setTimeout(()=>{try{forceVisible()}catch(e){}},400);
setTimeout(()=>{if(localStorage.getItem('vk_notif_prompt_shown'))return;const regOpen=!document.getElementById('registrationModal').hidden;if(regOpen)return;document.getElementById('notifPermissionModal').hidden=false;localStorage.setItem('vk_notif_prompt_shown','1')},2500);
</script>
</body>
</html>

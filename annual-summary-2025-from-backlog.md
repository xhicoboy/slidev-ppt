---
theme: default
title: 2025年度工作总结与规划（基于需求列表）
info: |
  ## 2025年度工作总结与规划（基于需求列表）
  汇报人：唐新志 | 部门：研发部 | 岗位：前端开发工程师
drawings:
  persist: false
transition: slide-left
mdc: true
css: styles.css
---

# 2025年度工作总结与规划

**（基于年度需求列表/Story交付清单）**  
**汇报人：唐新志 | 部门：研发部 | 岗位：前端开发工程师**

---
layout: cover
background: '#ffffff'
class: text-gray-800
---

<div class="logo-container">
  <div class="logo-bg">
    <div class="text-green-600 text-xl">🐴</div>
    <div>
      <div class="logo-text">瞬马科技</div>
      <div class="logo-subtext">BOON MASTER TECH</div>
    </div>
  </div>
</div>

<div class="flex h-full">
  <div class="flex-1 flex flex-col justify-center pl-20">
    <h1 class="text-7xl font-bold text-gray-800 mb-4">目录</h1>
    <h2 class="text-4xl text-gray-600">CONTENTS</h2>
  </div>
  
  <div class="flex-1 flex flex-col justify-center pr-20">
    <div class="space-y-8">
      <div class="flex items-center">
        <div class="diamond-number"><span>1</span></div>
        <div class="flex flex-col">
          <span class="text-3xl font-semibold text-gray-800">业绩回顾</span>
          <span class="text-xl text-gray-600 mt-1">Performance Review</span>
        </div>
      </div>
      <div class="flex items-center">
        <div class="diamond-number"><span>2</span></div>
        <div class="flex flex-col">
          <span class="text-3xl font-semibold text-gray-800">成长回顾</span>
          <span class="text-xl text-gray-600 mt-1">Growth & Development</span>
        </div>
      </div>
      <div class="flex items-center">
        <div class="diamond-number"><span>3</span></div>
        <div class="flex flex-col">
          <span class="text-3xl font-semibold text-gray-800">感受与建议</span>
          <span class="text-xl text-gray-600 mt-1">Reflections & Suggestions</span>
        </div>
      </div>
      <div class="flex items-center">
        <div class="diamond-number"><span>4</span></div>
        <div class="flex flex-col">
          <span class="text-3xl font-semibold text-gray-800">未来规划</span>
          <span class="text-xl text-gray-600 mt-1">Future Planning</span>
        </div>
      </div>
    </div>
  </div>
</div>

---
layout: section
background: '#f9fafb'
---

# Part 1. 业绩回顾：聚焦交付与增长

<div class="mt-8 p-4 bg-green-50 border-l-4 border-green-500 rounded">
  <p class="text-lg font-semibold text-gray-800">交付概览（来自需求列表截图）</p>
  <ul class="text-gray-700 mt-2 space-y-1 text-sm">
    <li>• 覆盖 <strong>Anonsms、FMP、Costext、反查（含马甲）、ClarityVerify、统一管理后台</strong> 等多条业务线</li>
    <li>• 状态以 <strong>已实现</strong> 为主，少量需求处于 <strong>测试中</strong> / <strong>实现中</strong></li>
    <li>• 优先级以 <strong>High/Middle</strong> 为主，集中在 <strong>重构、SEO/合规、转化/支付、埋点与数据闭环</strong></li>
    <li>• 时间跨度覆盖 <strong>2024-12 ~ 2025-12</strong>，存在明显的多线并行与版本迭代节奏</li>
  </ul>
</div>

---
layout: default
---

## 1.1 FMP：页面重构 + 多语言落地 + SEO治理

<div class="mt-6 grid grid-cols-2 gap-4">
  <div class="p-4 bg-blue-50 rounded-lg border-l-4 border-blue-500">
    <p class="font-bold text-blue-700 mb-2">核心交付</p>
    <ul class="text-sm text-gray-700 space-y-1">
      <li>• <strong>[FMP] 1.8</strong> find-people 页面重构（已实现）</li>
      <li>• <strong>[FMP] 1.10</strong> 反查页面重构（已实现）</li>
      <li>• <strong>落地页扩展</strong>：意/英/法/土/西/葡/巴西等语种与页面新增（已实现）</li>
    </ul>
  </div>
  <div class="p-4 bg-green-50 rounded-lg border-l-4 border-green-500">
    <p class="font-bold text-green-700 mb-2">增长与合规支撑</p>
    <ul class="text-sm text-gray-700 space-y-1">
      <li>• <strong>SEO内容优化</strong>（已实现）</li>
      <li>• <strong>robots 调整</strong>、站点地图同步、页头页脚统一（已实现）</li>
      <li>• <strong>过审站</strong>公司信息补充、价格模块优化（已实现）</li>
    </ul>
  </div>
</div>

---
layout: default
---

## 1.2 Anonsms：产品迭代 + 转化提升 + 数据闭环

<div class="mt-6 grid grid-cols-2 gap-4">
  <div class="p-4 bg-purple-50 rounded-lg border-l-4 border-purple-500">
    <p class="font-bold text-purple-700 mb-2">产品功能与运营场景</p>
    <ul class="text-sm text-gray-700 space-y-1">
      <li>• <strong>星座运势</strong>功能改造、短信能力补充（已实现）</li>
      <li>• <strong>Anonsms-Bulk</strong> 批量发送与介绍页优化（已实现）</li>
      <li>• <strong>早安短信 / SaySorry / 恶作剧主题短信</strong> 等内容型产品（已实现）</li>
    </ul>
  </div>
  <div class="p-4 bg-orange-50 rounded-lg border-l-4 border-orange-500">
    <p class="font-bold text-orange-700 mb-2">转化与增长基础设施</p>
    <ul class="text-sm text-gray-700 space-y-1">
      <li>• <strong>收银台体验</strong>：loading 优化、优惠挽回弹窗（已实现）</li>
      <li>• <strong>SEO需求</strong>：结构化数据 & OpenGraph、页面标题/描述更新（已实现）</li>
      <li>• <strong>埋点补齐</strong>：留言板查看、星座运势、站点行为等（已实现）</li>
      <li>• <strong>语种治理</strong>：下线越南/印尼语（已实现）</li>
    </ul>
  </div>
</div>

---
layout: default
---

## 1.3 Costext：支付链路稳定性 + 投放对接

<div class="mt-6 grid grid-cols-2 gap-4">
  <div class="p-4 bg-cyan-50 rounded-lg border-l-4 border-cyan-500">
    <p class="font-bold text-cyan-700 mb-2">支付与收银台链路</p>
    <ul class="text-sm text-gray-700 space-y-1">
      <li>• <strong>收银台模板更新</strong>（已实现，含业务侧对接）</li>
      <li>• <strong>SMS 发送成功页</strong>改造（已实现）</li>
      <li>• <strong>支付成功埋点</strong>（前后端补齐与联调）（已实现）</li>
    </ul>
  </div>
  <div class="p-4 bg-indigo-50 rounded-lg border-l-4 border-indigo-500">
    <p class="font-bold text-indigo-700 mb-2">投放与数据闭环</p>
    <ul class="text-sm text-gray-700 space-y-1">
      <li>• <strong>增加投放代码</strong> 与关键点位埋点（已实现）</li>
      <li>• <strong>账号体系与通用模板</strong>建设（已实现）</li>
      <li>• <strong>性能优化</strong>（已实现）</li>
    </ul>
  </div>
</div>

---
layout: default
---

## 1.4 反查：多版本马甲交付 + 结果体验优化

<div class="mt-6 grid grid-cols-2 gap-4">
  <div class="p-4 bg-yellow-50 rounded-lg border-l-4 border-yellow-500">
    <p class="font-bold text-yellow-700 mb-2">版本交付（马甲）</p>
    <ul class="text-sm text-gray-700 space-y-1">
      <li>• <strong>马甲 1.3~1.6</strong>（已实现）</li>
      <li>• <strong>马甲 1.7/1.8</strong>（已实现）</li>
      <li>• <strong>反查 1.0 套餐更新</strong>（已实现，含前端）</li>
    </ul>
  </div>
  <div class="p-4 bg-emerald-50 rounded-lg border-l-4 border-emerald-500">
    <p class="font-bold text-emerald-700 mb-2">体验与业务规则</p>
    <ul class="text-sm text-gray-700 space-y-1">
      <li>• <strong>试用价格名称</strong>调整（已实现）</li>
      <li>• <strong>人物搜索结果</strong>补充关联电话号码（测试中）</li>
      <li>• <strong>反查马甲埋点</strong>与数据闭环（已实现）</li>
    </ul>
  </div>
</div>

---
layout: default
---

## 1.5 统一管理后台 & 合规：支撑业务连续性

<div class="mt-6 grid grid-cols-2 gap-4">
  <div class="p-4 bg-gray-50 rounded-lg border-l-4 border-gray-400">
    <p class="font-bold text-gray-700 mb-2">管理后台</p>
    <ul class="text-sm text-gray-700 space-y-1">
      <li>• <strong>反查购买历程表单</strong>新增与数据调整（已实现）</li>
      <li>• <strong>争议表</strong>查询与状态保留类需求（已实现）</li>
    </ul>
  </div>
  <div class="p-4 bg-red-50 rounded-lg border-l-4 border-red-500">
    <p class="font-bold text-red-700 mb-2">合规与站点建设</p>
    <ul class="text-sm text-gray-700 space-y-1">
      <li>• <strong>海外过审整改</strong>：美国V/Adyen/Onepdf 等合规要求（已实现）</li>
      <li>• <strong>ClarityVerify 新站点</strong>建设（已实现），页脚版权替换（实现中）</li>
      <li>• <strong>域名与 robots</strong>策略梳理、防爬虫机制（已实现）</li>
    </ul>
  </div>
</div>

---
layout: section
background: '#f9fafb'
---

# Part 2. 成长回顾：方法论沉淀与能力升级

---
layout: default
---

## 2.1 工程能力：从“实现功能”到“可持续交付”

<div class="mt-6 grid grid-cols-2 gap-4">
  <div class="p-5 bg-blue-50 rounded-lg">
    <p class="text-xl font-bold text-blue-700 mb-2">复杂重构能力</p>
    <ul class="text-sm text-gray-700 space-y-1">
      <li>• 多版本并行（1.3~1.10），重构与迭代交错推进</li>
      <li>• 页面重构（find-people / 反查）过程中更强调结构收敛与复用</li>
    </ul>
  </div>
  <div class="p-5 bg-green-50 rounded-lg">
    <p class="text-xl font-bold text-green-700 mb-2">跨站点治理能力</p>
    <ul class="text-sm text-gray-700 space-y-1">
      <li>• 多语言落地页建设与发布节奏控制</li>
      <li>• robots/sitemap/TDK/结构化数据等SEO治理形成固定套路</li>
    </ul>
  </div>
</div>

---
layout: default
---

## 2.2 数据与增长：从“做页面”到“做闭环”

<div class="mt-6 grid grid-cols-2 gap-4">
  <div class="p-5 bg-purple-50 rounded-lg">
    <p class="text-xl font-bold text-purple-700 mb-2">埋点体系意识</p>
    <ul class="text-sm text-gray-700 space-y-1">
      <li>• 多业务线关键路径补齐埋点（产品、投放、支付成功）</li>
      <li>• 能用“漏斗视角”审视收银台、成功页、挽回弹窗的价值</li>
    </ul>
  </div>
  <div class="p-5 bg-orange-50 rounded-lg">
    <p class="text-xl font-bold text-orange-700 mb-2">投放与转化协作</p>
    <ul class="text-sm text-gray-700 space-y-1">
      <li>• 投放代码接入与关键事件闭环</li>
      <li>• 转化链路体验优化（loading、弹窗、成功页）</li>
    </ul>
  </div>
</div>

---
layout: default
---

## 2.3 协作影响力：跨角色共识与交付稳定性

<div class="mt-6 grid grid-cols-3 gap-4">
  <div class="p-4 bg-gray-50 rounded-lg text-center">
    <div class="text-4xl mb-2">🤝</div>
    <p class="font-bold text-gray-800 mb-1">跨团队协作</p>
    <p class="text-xs text-gray-600">支付、合规、SEO、后台等多域协同，交付节奏更可控。</p>
  </div>
  <div class="p-4 bg-gray-50 rounded-lg text-center">
    <div class="text-4xl mb-2">🧩</div>
    <p class="font-bold text-gray-800 mb-1">需求拆解</p>
    <p class="text-xs text-gray-600">把“功能/体验/数据/合规”拆成可验收的子目标，减少返工。</p>
  </div>
  <div class="p-4 bg-gray-50 rounded-lg text-center">
    <div class="text-4xl mb-2">🧯</div>
    <p class="font-bold text-gray-800 mb-1">风险意识</p>
    <p class="text-xs text-gray-600">对“多版本马甲+多站点”组合，能更早识别发布与兼容风险。</p>
  </div>
</div>

---
layout: section
background: '#f9fafb'
---

# Part 3. 感受与建议：提质增效的关键抓手

---
layout: default
---

## 3.1 年度感受

<div class="mt-6 space-y-4">
  <div class="p-4 bg-blue-50 rounded border-l-4 border-blue-400">
    <p class="font-bold text-blue-800">多线并行是常态</p>
    <p class="text-sm text-blue-700">同一时间需要兼顾重构、合规、SEO、投放与转化优化，交付的难点不在“写代码”，而在“把复杂度控制住”。</p>
  </div>
  <div class="p-4 bg-green-50 rounded border-l-4 border-green-400">
    <p class="font-bold text-green-800">数据闭环价值越来越高</p>
    <p class="text-sm text-green-700">需求列表里大量“埋点/投放/支付成功链路”类工作，说明业务进入精细化运营阶段，工程侧必须更体系化。</p>
  </div>
  <div class="p-4 bg-orange-50 rounded border-l-4 border-orange-400">
    <p class="font-bold text-orange-800">合规与SEO是海外业务的“底座能力”</p>
    <p class="text-sm text-orange-700">过审整改、robots、防爬与结构化数据治理，对业务连续性影响极大，值得流程化与自动化。</p>
  </div>
</div>

---
layout: default
---

## 3.2 建议（面向团队/流程）

<div class="mt-6 grid grid-cols-2 gap-4">
  <div class="p-4 bg-purple-50 rounded border-l-4 border-purple-400">
    <p class="font-bold text-purple-800">建议 1：建立“发布与多版本马甲”规范</p>
    <p class="text-xs text-purple-700 mt-1">沉淀版本差异清单、回滚策略与验证清单，降低并行版本导致的兼容与遗漏风险。</p>
  </div>
  <div class="p-4 bg-indigo-50 rounded border-l-4 border-indigo-400">
    <p class="font-bold text-indigo-800">建议 2：埋点标准化 + 自动验收</p>
    <p class="text-xs text-indigo-700 mt-1">统一命名/事件字典，关键漏斗（支付/成功页/挽回）引入自动化校验，避免“上线即脏数据”。</p>
  </div>
  <div class="p-4 bg-green-50 rounded border-l-4 border-green-400">
    <p class="font-bold text-green-800">建议 3：SEO/合规 Checklist 化</p>
    <p class="text-xs text-green-700 mt-1">robots、sitemap、TDK、OpenGraph、结构化数据与隐私合规统一检查项，发布前自动/半自动验证。</p>
  </div>
  <div class="p-4 bg-orange-50 rounded border-l-4 border-orange-400">
    <p class="font-bold text-orange-800">建议 4：i18n 管理平台化</p>
    <p class="text-xs text-orange-700 mt-1">多语种落地页扩张后，建议引入翻译平台/同步流程，减少人工合并与漏翻风险。</p>
  </div>
</div>

---
layout: section
background: '#f9fafb'
---

# Part 4. 未来规划：技术牵引业务的可持续增长

---
layout: default
---

## 4.1 2026 工作主线（建议方向）

<div class="mt-6 grid grid-cols-3 gap-4">
  <div class="p-5 bg-gray-50 rounded-lg border border-gray-200">
    <p class="text-xl font-bold text-gray-800 mb-2">产能</p>
    <p class="text-sm text-gray-600">跨站点通用能力沉淀，降低重复开发，提升并行交付上限。</p>
  </div>
  <div class="p-5 bg-gray-50 rounded-lg border border-gray-200">
    <p class="text-xl font-bold text-gray-800 mb-2">质量</p>
    <p class="text-sm text-gray-600">把“合规/SEO/埋点”前置为流程与工具，减少发布风险与返工。</p>
  </div>
  <div class="p-5 bg-gray-50 rounded-lg border border-gray-200">
    <p class="text-xl font-bold text-gray-800 mb-2">增长</p>
    <p class="text-sm text-gray-600">围绕支付漏斗与投放闭环深挖提升点，工程侧输出可复用的增长抓手。</p>
  </div>
</div>

---
layout: default
---

## 4.2 重点落地项目（可量化）

<div class="mt-6 space-y-4">
  <div class="p-4 bg-blue-50 rounded border-l-4 border-blue-400">
    <p class="font-bold text-blue-800">项目 A：跨业务线通用组件/模板库</p>
    <p class="text-sm text-blue-700">沉淀收银台、成功页、弹窗、落地页布局等高复用模块，形成“模板化交付”。</p>
  </div>
  <div class="p-4 bg-purple-50 rounded border-l-4 border-purple-400">
    <p class="font-bold text-purple-800">项目 B：埋点字典 + 校验工具</p>
    <p class="text-sm text-purple-700">建立事件字典、关键路径自动校验，持续提升数据可用性与迭代效率。</p>
  </div>
  <div class="p-4 bg-green-50 rounded border-l-4 border-green-400">
    <p class="font-bold text-green-800">项目 C：SEO/合规自动化检查</p>
    <p class="text-sm text-green-700">把 robots/sitemap/OG/结构化数据/隐私条款等纳入发布前检查，减少“临时整改”。</p>
  </div>
</div>

---
layout: default
---

## 4.3 个人成长目标（建议）

<div class="mt-6 grid grid-cols-2 gap-4">
  <div class="p-5 bg-indigo-50 rounded-lg">
    <p class="text-xl font-bold text-indigo-700 mb-2">技术深度</p>
    <ul class="text-sm text-gray-700 space-y-1">
      <li>• 工程化与构建体系：发布/多版本/多站点治理</li>
      <li>• 性能体系：关键页面性能预算与监控闭环</li>
    </ul>
  </div>
  <div class="p-5 bg-orange-50 rounded-lg">
    <p class="text-xl font-bold text-orange-700 mb-2">业务影响力</p>
    <ul class="text-sm text-gray-700 space-y-1">
      <li>• 以数据为依据，推动 2~3 个支付漏斗的关键优化落地</li>
      <li>• 形成可复用的“增长技术方案”，减少一次性实现</li>
    </ul>
  </div>
</div>

---
layout: default
---

## 附：代表性需求清单（按业务线聚类）

<div class="mt-6 grid grid-cols-2 gap-4 text-sm">
  <div class="p-4 bg-gray-50 rounded border border-gray-200">
    <p class="font-bold text-gray-800 mb-2">FMP</p>
    <ul class="text-gray-700 space-y-1">
      <li>• [FMP] 1.8 find-people 页面重构（已实现）</li>
      <li>• [FMP] 1.10 反查页面重构（已实现）</li>
      <li>• 多语种落地页扩展（已实现）</li>
      <li>• robots / sitemap / SEO 内容优化（已实现）</li>
    </ul>
  </div>
  <div class="p-4 bg-gray-50 rounded border border-gray-200">
    <p class="font-bold text-gray-800 mb-2">Anonsms</p>
    <ul class="text-gray-700 space-y-1">
      <li>• 星座运势改造/短信能力补充（已实现）</li>
      <li>• 批量发送（Bulk）与介绍页优化（已实现）</li>
      <li>• 收银台 loading / 优惠挽回弹窗（已实现）</li>
      <li>• 结构化数据 & OG / TDK 更新（已实现）</li>
    </ul>
  </div>
  <div class="p-4 bg-gray-50 rounded border border-gray-200">
    <p class="font-bold text-gray-800 mb-2">Costext</p>
    <ul class="text-gray-700 space-y-1">
      <li>• 收银台模板更新（已实现）</li>
      <li>• SMS 发送成功页改造（已实现）</li>
      <li>• 投放代码接入 & 埋点（已实现）</li>
      <li>• 支付成功埋点（前后端补齐）（已实现）</li>
    </ul>
  </div>
  <div class="p-4 bg-gray-50 rounded border border-gray-200">
    <p class="font-bold text-gray-800 mb-2">反查/后台/合规</p>
    <ul class="text-gray-700 space-y-1">
      <li>• 马甲 1.3~1.8 / 套餐更新（已实现）</li>
      <li>• 人物搜索结果关联手机号（测试中）</li>
      <li>• 管理后台购买历程表单优化（已实现）</li>
      <li>• 海外过审整改 & ClarityVerify 站点（部分实现中）</li>
    </ul>
  </div>
</div>

---
layout: cover
background: '#10b981'
class: text-white
---

# 结语

<div class="mt-10 text-2xl leading-relaxed">
  <p class="mb-6">这一年，在多业务线、多版本、多站点的压力下，依然把“重构、SEO/合规、支付与数据闭环”做到可交付、可复用。</p>
  <p class="mb-6">下一年，把这些能力沉淀为工具与规范，让团队交付更稳、更快、更能驱动增长。</p>
</div>

<div class="absolute bottom-10 right-10 text-lg opacity-80">
  汇报人：唐新志 | 2025.12.18
</div>



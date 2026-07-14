# 协同办公应用

这是协同办公应用的前端工程目录。

产品聚焦会议预定、流程审批、差旅出行、文档查询、请假打卡五大高频办公场景，目标是让员工在移动端用更少步骤完成日常协同动作。

## 本地运行

### 环境要求

- Node.js 18 或更高版本
- Gemini API Key

### 安装依赖

```bash
npm install
```

### 配置环境变量

```bash
cp .env.example .env.local
```

在 `.env.local` 中填入：

```bash
GEMINI_API_KEY=your_gemini_api_key
```

### 启动开发服务器

```bash
npm run dev
```

默认访问地址：

```text
http://localhost:3000
```

## 常用命令

```bash
npm run dev      # 启动本地开发服务器
npm run build    # 构建生产版本
npm run preview  # 预览生产构建
npm run lint     # TypeScript 类型检查
```

## 主要技术

- React 19
- TypeScript
- Vite 6
- Tailwind CSS 4
- Motion
- Lucide React
- React Markdown
- Google Gemini AI

更多产品说明请查看仓库根目录的 [README.md](../README.md)。

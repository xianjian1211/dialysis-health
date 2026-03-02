<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>透析健康管理系统</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; font-family: "Microsoft YaHei", "PingFang SC", sans-serif; }
        :root { --primary-color: #4a90e2; --primary-dark: #357abd; --secondary-color: #e74c3c; --secondary-dark: #c0392b; --success-color: #2ecc71; --warning-color: #f1c40f; --info-color: #3498db; --gray-light: #f8f9fa; --gray: #ecf0f1; --gray-dark: #7f8c8d; --text-color: #2c3e50; --shadow-sm: 0 2px 4px rgba(0,0,0,0.05); --shadow: 0 2px 10px rgba(0,0,0,0.08); --shadow-lg: 0 5px 15px rgba(0,0,0,0.1); --radius-sm: 5px; --radius: 8px; --radius-lg: 12px; --transition: all 0.3s ease; }
        body { background-color: #f5f7fa; color: var(--text-color); line-height: 1.6; font-size: 14px; padding-bottom: 20px; }
        
        /* 登录界面样式 */
        .login-container { 
            display: flex; 
            justify-content: center; 
            align-items: center; 
            min-height: 100vh;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            padding: 20px;
        }
        .login-box {
            background: white;
            border-radius: var(--radius-lg);
            padding: 40px;
            width: 100%;
            max-width: 400px;
            box-shadow: var(--shadow-lg);
        }
        .login-header {
            text-align: center;
            margin-bottom: 30px;
        }
        .login-header h1 {
            font-size: 24px;
            color: var(--primary-color);
            margin-bottom: 10px;

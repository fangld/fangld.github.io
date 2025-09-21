---
layout: page
permalink: /teaching/
title: Teaching
description: 
nav: true
nav_order: 6
---


<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        .container {
            max-width: 1000px;
            margin: 0 auto;
        }
        
        header {
            margin-bottom: 3rem;
        }
        
        .courses-container {
            display: flex;
            flex-direction: column;
            gap: 1.5rem;
        }
        
        .course-card {
            border: 1px solid #e0e6ed;
            background: var(--global-card-bg-color);
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.08);
            padding: 1.8rem;
            display: flex;
            align-items: flex-start;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            position: relative;
            overflow: hidden;
        }
        
        .course-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 15px 35px rgba(0, 0, 0, 0.12);
        }
        
        .course-card::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 6px;
            height: 100%;
            background: linear-gradient(to bottom, #3498db, #2c3e50);
        }
        
        .course-icon {
            background: linear-gradient(135deg, #3498db 0%, #2c3e50 100%);
            width: 60px;
            height: 60px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            margin-right: 1.5rem;
            flex-shrink: 0;
        }
        
        .course-icon i {
            font-size: 1.8rem;
            color: white;
        }
        
        .course-content {
            flex-grow: 1;
        }
        
        .course-title {
            font-size: 1.5rem;
            color: var(--global-theme-color);
            margin-bottom: 0.8rem;
            font-weight: 600;
        }
        
        .course-period {
            display: inline-block;
            background: linear-gradient(to right, #e3f2fd, #bbdefb);
            color: #1565c0;
            padding: 0.4rem 1rem;
            border-radius: 20px;
            font-size: 0.9rem;
            font-weight: 500;
            margin-bottom: 1rem;
        }
        
        .semester-tags {
            display: flex;
            flex-wrap: wrap;
            gap: 0.6rem;
            margin-top: 1rem;
        }
        
        .semester-tag {
            background: #f5f7fa;
            padding: 0.4rem 0.8rem;
            border-radius: 6px;
            font-size: 0.85rem;
            display: flex;
            align-items: center;
            border: 1px solid #e0e6ed;
        }
        
        .semester-tag i {
            margin-right: 0.4rem;
            color: #3498db;
            font-size: 0.7rem;
        }
        
        .spring {
            background: #e8f5e9;
            color: #388e3c;
            border-color: #c8e6c9;
        }
        
        .fall {
            background: #e3f2fd;
            color: #1565c0;
            border-color: #bbdefb;
        }
        
        .graduated {
            background: #f3e5f5;
            color: #7b1fa2;
            border-color: #e1bee7;
        }
        
        footer {
            text-align: center;
            margin-top: 3rem;
            color: #7f8c8d;
            font-size: 0.9rem;
        }
        
        @media (max-width: 768px) {
            .course-card {
                flex-direction: column;
                align-items: center;
                text-align: center;
            }
            
            .course-icon {
                margin-right: 0;
                margin-bottom: 1.2rem;
            }
            
            .semester-tags {
                justify-content: center;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="courses-container">   
            <div class="course-card">
                <div class="course-icon">
                    <i class="fas fa-calculator"></i>
                </div>
                <div class="course-content">
                    <h2 class="course-title">Numerical Analysis</h2>
                    <span class="course-period">Fall 2016 - 2025</span>
                    <p>Advanced course covering numerical methods for solving mathematical problems, including interpolation, differentiation, integration, and differential equations.</p>
                </div>
            </div>
            <div class="course-card">
                <div class="course-icon">
                    <i class="fas fa-brain"></i>
                </div>
                <div class="course-content">
                    <h2 class="course-title">Mathematical Logics</h2>
                    <span class="course-period">Graduated Courses</span>
                    <p>Graduate-level course exploring advanced topics in mathematical logic, including set theory, model theory, and proof theory.</p>
                    <div class="semester-tags">
                        <span class="semester-tag spring"><i class="fas fa-seedling"></i> Spring 2017</span>
                        <span class="semester-tag spring"><i class="fas fa-seedling"></i> Spring 2024</span>
                        <span class="semester-tag spring"><i class="fas fa-seedling"></i> Spring 2025</span>
                        <span class="semester-tag fall"><i class="fas fa-leaf"></i> Fall 2017</span>
                        <span class="semester-tag fall"><i class="fas fa-leaf"></i> Fall 2018</span>
                        <span class="semester-tag fall"><i class="fas fa-leaf"></i> Fall 2019</span>
                        <span class="semester-tag fall"><i class="fas fa-leaf"></i> Fall 2020</span>
                        <span class="semester-tag fall"><i class="fas fa-leaf"></i> Fall 2021</span>
                        <span class="semester-tag fall"><i class="fas fa-leaf"></i> Fall 2022</span>
                    </div>
                </div>
            </div>
            <div class="course-card">
                <div class="course-icon">
                    <i class="fas fa-network-wired"></i>
                </div>
                <div class="course-content">
                    <h2 class="course-title">Distributed Computation</h2>
                    <span class="course-period">Spring 2017</span>
                    <p>Course focusing on the principles and practices of distributed computing systems, including algorithms, architectures, and consistency models.</p>
                </div>
            </div>
        </div>
    </div>
</body>
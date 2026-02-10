<index html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Otocinclus - HR Consultancy & HRMS Implementation Partner | Remove the Admin Trap</title>
    <meta name="description" content="Otocinclus: Your trusted HR Consultancy and HRMS Implementation Partner. Remove the Admin Trap with integrated HR infrastructure. Flat 7% recruitment for all levels. Audit. Advise. Implement. Transfer.">
    <meta name="keywords" content="HR consultancy, HRMS implementation, payroll services, recruitment services, HR compliance, employee management, Bangalore HR services, affordable HR solutions">
    <style>
        :root {
            --primary-teal: #218D8D;
            --primary-blue: #3B82F6;
            --accent-orange: #F97316;
            --dark-charcoal: #1F2121;
            --cream-bg: #FCFCF9;
            --white: #FFFFFF;
            --gray-text: #626C71;
            --light-gray: #F5F5F5;
            --border-color: rgba(94, 82, 64, 0.2);
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', 'Roboto', 'Helvetica Neue', Arial, sans-serif;
            line-height: 1.6;
            color: var(--dark-charcoal);
            background: var(--cream-bg);
            overflow-x: hidden;
        }

        /* Navigation */
        .navbar {
            position: fixed;
            top: 0;
            width: 100%;
            background: rgba(252, 252, 249, 0.95);
            backdrop-filter: blur(10px);
            padding: 1rem 0;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.05);
            z-index: 1000;
            transition: all 0.3s ease;
        }

        .navbar.scrolled {
            padding: 0.5rem 0;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
        }

        .nav-container {
            max-width: 1400px;
            margin: 0 auto;
            padding: 0 2rem;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .logo-container {
            display: flex;
            align-items: center;
            gap: 1rem;
        }

        .logo {
            height: 50px;
            transition: transform 0.3s ease;
        }

        .logo:hover {
            transform: scale(1.05);
        }

        .nav-links {
            display: flex;
            gap: 2.5rem;
            list-style: none;
            align-items: center;
        }

        .nav-links a {
            text-decoration: none;
            color: var(--dark-charcoal);
            font-weight: 500;
            font-size: 0.95rem;
            transition: color 0.3s ease;
            position: relative;
        }

        .nav-links a::after {
            content: '';
            position: absolute;
            bottom: -5px;
            left: 0;
            width: 0;
            height: 2px;
            background: var(--primary-teal);
            transition: width 0.3s ease;
        }

        .nav-links a:hover::after {
            width: 100%;
        }

        .nav-links a:hover {
            color: var(--primary-teal);
        }

        .cta-button {
            background: var(--primary-teal);
            color: var(--white);
            padding: 0.75rem 1.5rem;
            border-radius: 8px;
            text-decoration: none;
            font-weight: 600;
            transition: all 0.3s ease;
            box-shadow: 0 4px 15px rgba(33, 141, 141, 0.2);
        }

        .cta-button:hover {
            background: #1a7070;
            transform: translateY(-2px);
            box-shadow: 0 6px 20px rgba(33, 141, 141, 0.3);
        }

        .mobile-menu {
            display: none;
            flex-direction: column;
            gap: 6px;
            cursor: pointer;
        }

        .mobile-menu span {
            width: 25px;
            height: 3px;
            background: var(--dark-charcoal);
            transition: all 0.3s ease;
        }

        /* Hero Section with Slideshow */
        .hero {
            margin-top: 80px;
            min-height: 90vh;
            display: flex;
            align-items: center;
            position: relative;
            overflow: hidden;
            background: linear-gradient(135deg, var(--cream-bg) 0%, #e8f5f5 100%);
        }

        .hero-content {
            max-width: 1400px;
            margin: 0 auto;
            padding: 4rem 2rem;
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 4rem;
            align-items: center;
        }

        .hero-text h1 {
            font-size: 3.5rem;
            font-weight: 700;
            line-height: 1.2;
            margin-bottom: 1.5rem;
            color: var(--dark-charcoal);
        }

        .hero-text .tagline {
            font-size: 1.5rem;
            color: var(--primary-teal);
            font-weight: 600;
            margin-bottom: 1rem;
        }

        .hero-text p {
            font-size: 1.2rem;
            color: var(--gray-text);
            margin-bottom: 2rem;
            line-height: 1.8;
        }

        .hero-buttons {
            display: flex;
            gap: 1rem;
            flex-wrap: wrap;
        }

        .hero-buttons .btn-primary {
            background: var(--primary-teal);
            color: var(--white);
            padding: 1rem 2.5rem;
            border-radius: 8px;
            text-decoration: none;
            font-weight: 600;
            font-size: 1.1rem;
            transition: all 0.3s ease;
            box-shadow: 0 4px 15px rgba(33, 141, 141, 0.2);
        }

        .hero-buttons .btn-primary:hover {
            transform: translateY(-3px);
            box-shadow: 0 6px 25px rgba(33, 141, 141, 0.3);
        }

        .hero-buttons .btn-secondary {
            background: transparent;
            color: var(--primary-teal);
            padding: 1rem 2.5rem;
            border: 2px solid var(--primary-teal);
            border-radius: 8px;
            text-decoration: none;
            font-weight: 600;
            font-size: 1.1rem;
            transition: all 0.3s ease;
        }

        .hero-buttons .btn-secondary:hover {
            background: var(--primary-teal);
            color: var(--white);
            transform: translateY(-3px);
        }

        /* Slideshow Container */
        .slideshow-container {
            position: relative;
            width: 100%;
            max-width: 600px;
        }

        .slide {
            display: none;
            animation: fadeIn 1s ease-in-out;
        }

        .slide.active {
            display: block;
        }

        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }

        .value-card {
            background: var(--white);
            border-radius: 20px;
            padding: 3rem;
            box-shadow: 0 10px 40px rgba(0, 0, 0, 0.1);
            text-align: center;
            transition: transform 0.3s ease;
        }

        .value-card:hover {
            transform: translateY(-10px);
        }

        .value-icon {
            width: 100px;
            height: 100px;
            margin: 0 auto 1.5rem;
            display: flex;
            align-items: center;
            justify-content: center;
            background: linear-gradient(135deg, var(--primary-teal) 0%, var(--primary-blue) 100%);
            border-radius: 50%;
            font-size: 3rem;
            color: var(--white);
        }

        .value-card h2 {
            font-size: 2rem;
            margin-bottom: 1rem;
            color: var(--dark-charcoal);
        }

        .value-card .percentage {
            font-size: 3.5rem;
            font-weight: 700;
            color: var(--primary-teal);
            margin: 1rem 0;
        }

        .value-card p {
            font-size: 1.1rem;
            color: var(--gray-text);
            line-height: 1.8;
        }

        .value-card ul {
            list-style: none;
            text-align: left;
            margin-top: 1.5rem;
        }

        .value-card li {
            padding: 0.5rem 0;
            font-size: 1rem;
            color: var(--gray-text);
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }

        .value-card li::before {
            content: '✓';
            color: var(--primary-teal);
            font-weight: 700;
            font-size: 1.2rem;
        }

        .slide-dots {
            text-align: center;
            margin-top: 1.5rem;
        }

        .dot {
            height: 12px;
            width: 12px;
            margin: 0 5px;
            background-color: #ddd;
            border-radius: 50%;
            display: inline-block;
            transition: background-color 0.3s ease;
            cursor: pointer;
        }

        .dot.active {
            background-color: var(--primary-teal);
        }

        /* Section Styles */
        section {
            padding: 6rem 2rem;
            max-width: 1400px;
            margin: 0 auto;
        }

        .section-header {
            text-align: center;
            margin-bottom: 4rem;
        }

        .section-header h2 {
            font-size: 3rem;
            font-weight: 700;
            margin-bottom: 1rem;
            color: var(--dark-charcoal);
        }

        .section-header p {
            font-size: 1.2rem;
            color: var(--gray-text);
            max-width: 800px;
            margin: 0 auto;
        }

        /* Value Proposition Section */
        .value-props {
            background: linear-gradient(135deg, #e8f5f5 0%, var(--cream-bg) 100%);
            padding: 6rem 2rem;
        }

        .value-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(400px, 1fr));
            gap: 3rem;
            max-width: 1400px;
            margin: 0 auto;
        }

        .value-item {
            background: var(--white);
            border-radius: 20px;
            padding: 3rem;
            box-shadow: 0 10px 40px rgba(0, 0, 0, 0.08);
            transition: all 0.3s ease;
        }

        .value-item:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 50px rgba(0, 0, 0, 0.12);
        }

        .value-item-icon {
            width: 80px;
            height: 80px;
            background: linear-gradient(135deg, var(--primary-teal) 0%, var(--primary-blue) 100%);
            border-radius: 15px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 2.5rem;
            color: var(--white);
            margin-bottom: 1.5rem;
        }

        .value-item h3 {
            font-size: 1.8rem;
            margin-bottom: 1rem;
            color: var(--dark-charcoal);
        }

        .value-item p {
            font-size: 1.1rem;
            color: var(--gray-text);
            line-height: 1.8;
            margin-bottom: 1.5rem;
        }

        /* Services Section */
        .services {
            background: var(--white);
        }

        .service-tabs {
            display: flex;
            justify-content: center;
            gap: 1rem;
            margin-bottom: 3rem;
            flex-wrap: wrap;
        }

        .tab-button {
            padding: 1rem 2rem;
            border: 2px solid var(--border-color);
            background: transparent;
            border-radius: 50px;
            font-size: 1rem;
            font-weight: 600;
            cursor: pointer;
            transition: all 0.3s ease;
            color: var(--dark-charcoal);
        }

        .tab-button.active {
            background: var(--primary-teal);
            color: var(--white);
            border-color: var(--primary-teal);
        }

        .tab-button:hover {
            border-color: var(--primary-teal);
        }

        .service-content {
            display: none;
        }

        .service-content.active {
            display: block;
            animation: fadeIn 0.5s ease-in-out;
        }

        .service-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
            gap: 2rem;
        }

        .service-card {
            background: var(--cream-bg);
            border-radius: 15px;
            padding: 2.5rem;
            transition: all 0.3s ease;
            border: 2px solid transparent;
        }

        .service-card:hover {
            border-color: var(--primary-teal);
            transform: translateY(-5px);
            box-shadow: 0 10px 30px rgba(33, 141, 141, 0.1);
        }

        .service-card h3 {
            font-size: 1.5rem;
            margin-bottom: 1rem;
            color: var(--primary-teal);
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }

        .service-card h3::before {
            content: '';
            width: 6px;
            height: 30px;
            background: var(--primary-teal);
            border-radius: 3px;
        }

        .service-card ul {
            list-style: none;
        }

        .service-card li {
            padding: 0.6rem 0;
            color: var(--gray-text);
            display: flex;
            align-items: flex-start;
            gap: 0.5rem;
            font-size: 0.95rem;
        }

        .service-card li::before {
            content: '→';
            color: var(--primary-teal);
            font-weight: 700;
            flex-shrink: 0;
        }

        /* Models Section */
        .models {
            background: linear-gradient(135deg, var(--cream-bg) 0%, #e8f5f5 100%);
        }

        .model-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(500px, 1fr));
            gap: 3rem;
        }

        .model-card {
            background: var(--white);
            border-radius: 20px;
            padding: 3rem;
            box-shadow: 0 10px 40px rgba(0, 0, 0, 0.08);
            position: relative;
            overflow: hidden;
        }

        .model-card::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 5px;
            background: linear-gradient(90deg, var(--primary-teal) 0%, var(--primary-blue) 100%);
        }

        .model-badge {
            display: inline-block;
            background: var(--primary-teal);
            color: var(--white);
            padding: 0.5rem 1.5rem;
            border-radius: 50px;
            font-weight: 600;
            margin-bottom: 1.5rem;
            font-size: 0.9rem;
        }

        .model-card h3 {
            font-size: 2rem;
            margin-bottom: 1rem;
            color: var(--dark-charcoal);
        }

        .model-card .subtitle {
            font-size: 1.1rem;
            color: var(--gray-text);
            margin-bottom: 2rem;
            font-style: italic;
        }

        .model-phases {
            margin-top: 2rem;
        }

        .phase {
            background: var(--cream-bg);
            border-radius: 10px;
            padding: 1.5rem;
            margin-bottom: 1rem;
        }

        .phase h4 {
            font-size: 1.2rem;
            color: var(--primary-teal);
            margin-bottom: 0.8rem;
        }

        .phase ul {
            list-style: none;
        }

        .phase li {
            padding: 0.4rem 0;
            color: var(--gray-text);
            font-size: 0.95rem;
            display: flex;
            align-items: flex-start;
            gap: 0.5rem;
        }

        .phase li::before {
            content: '•';
            color: var(--primary-teal);
            font-weight: 700;
            font-size: 1.2rem;
        }

        /* Recruitment Section */
        .recruitment {
            background: var(--dark-charcoal);
            color: var(--white);
            text-align: center;
        }

        .recruitment .section-header h2,
        .recruitment .section-header p {
            color: var(--white);
        }

        .pricing-comparison {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            margin-top: 3rem;
        }

        .pricing-card {
            background: rgba(255, 255, 255, 0.05);
            border-radius: 15px;
            padding: 2.5rem;
            border: 2px solid rgba(255, 255, 255, 0.1);
            transition: all 0.3s ease;
        }

        .pricing-card.highlighted {
            background: var(--primary-teal);
            border-color: var(--primary-teal);
            transform: scale(1.05);
        }

        .pricing-card:hover {
            transform: translateY(-10px);
        }

        .pricing-card h3 {
            font-size: 1.5rem;
            margin-bottom: 1rem;
        }

        .pricing-card .price {
            font-size: 3rem;
            font-weight: 700;
            margin: 1rem 0;
            color: var(--accent-orange);
        }

        .pricing-card.highlighted .price {
            color: var(--white);
        }

        .pricing-card p {
            font-size: 1rem;
            opacity: 0.9;
            margin-bottom: 1.5rem;
        }

        .pricing-card ul {
            list-style: none;
            text-align: left;
        }

        .pricing-card li {
            padding: 0.5rem 0;
            font-size: 0.95rem;
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }

        .pricing-card li::before {
            content: '✓';
            color: var(--accent-orange);
            font-weight: 700;
        }

        .pricing-card.highlighted li::before {
            color: var(--white);
        }

        /* Customer Journey */
        .journey {
            background: var(--white);
        }

        .journey-flow {
            display: flex;
            justify-content: space-between;
            align-items: center;
            gap: 2rem;
            margin-top: 3rem;
            flex-wrap: wrap;
        }

        .journey-step {
            flex: 1;
            min-width: 200px;
            text-align: center;
            position: relative;
        }

        .journey-step::after {
            content: '→';
            position: absolute;
            right: -2rem;
            top: 50%;
            transform: translateY(-50%);
            font-size: 2rem;
            color: var(--primary-teal);
        }

        .journey-step:last-child::after {
            display: none;
        }

        .journey-icon {
            width: 80px;
            height: 80px;
            background: linear-gradient(135deg, var(--primary-teal) 0%, var(--primary-blue) 100%);
            border-radius: 50%;
            margin: 0 auto 1rem;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 2rem;
            color: var(--white);
        }

        .journey-step h4 {
            font-size: 1.2rem;
            margin-bottom: 0.5rem;
            color: var(--dark-charcoal);
        }

        .journey-step p {
            font-size: 0.9rem;
            color: var(--gray-text);
        }

        /* Case Studies */
        .case-studies {
            background: linear-gradient(135deg, var(--cream-bg) 0%, #e8f5f5 100%);
        }

        .case-study-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(400px, 1fr));
            gap: 2.5rem;
            margin-top: 3rem;
        }

        .case-study {
            background: var(--white);
            border-radius: 15px;
            padding: 2.5rem;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.08);
        }

        .case-study-header {
            display: flex;
            align-items: center;
            gap: 1rem;
            margin-bottom: 1.5rem;
        }

        .case-study-icon {
            width: 60px;
            height: 60px;
            background: linear-gradient(135deg, var(--primary-teal) 0%, var(--primary-blue) 100%);
            border-radius: 10px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1.5rem;
            color: var(--white);
        }

        .case-study h3 {
            font-size: 1.5rem;
            color: var(--dark-charcoal);
        }

        .case-study .industry {
            color: var(--gray-text);
            font-size: 0.9rem;
            font-style: italic;
        }

        .case-study p {
            color: var(--gray-text);
            line-height: 1.8;
            margin-bottom: 1.5rem;
        }

        .case-study-results {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 1rem;
            margin-top: 1.5rem;
        }

        .result-stat {
            text-align: center;
            padding: 1rem;
            background: var(--cream-bg);
            border-radius: 10px;
        }

        .result-stat .number {
            font-size: 2rem;
            font-weight: 700;
            color: var(--primary-teal);
        }

        .result-stat .label {
            font-size: 0.85rem;
            color: var(--gray-text);
            margin-top: 0.3rem;
        }

        /* Contact Section */
        .contact {
            background: var(--white);
        }

        .contact-container {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 4rem;
            align-items: start;
        }

        .contact-info {
            background: linear-gradient(135deg, var(--primary-teal) 0%, var(--primary-blue) 100%);
            color: var(--white);
            border-radius: 20px;
            padding: 3rem;
        }

        .contact-info h3 {
            font-size: 2rem;
            margin-bottom: 2rem;
        }

        .contact-item {
            display: flex;
            align-items: flex-start;
            gap: 1rem;
            margin-bottom: 2rem;
        }

        .contact-icon {
            width: 40px;
            height: 40px;
            background: rgba(255, 255, 255, 0.2);
            border-radius: 10px;
            display: flex;
            align-items: center;
            justify-content: center;
            flex-shrink: 0;
        }

        .contact-item h4 {
            font-size: 1rem;
            margin-bottom: 0.3rem;
        }

        .contact-item p {
            font-size: 0.95rem;
            opacity: 0.9;
        }

        .contact-form {
            background: var(--cream-bg);
            border-radius: 20px;
            padding: 3rem;
        }

        .contact-form h3 {
            font-size: 2rem;
            margin-bottom: 2rem;
            color: var(--dark-charcoal);
        }

        .form-group {
            margin-bottom: 1.5rem;
        }

        .form-group label {
            display: block;
            margin-bottom: 0.5rem;
            font-weight: 600;
            color: var(--dark-charcoal);
            font-size: 0.95rem;
        }

        .form-group input,
        .form-group textarea,
        .form-group select {
            width: 100%;
            padding: 1rem;
            border: 2px solid var(--border-color);
            border-radius: 8px;
            font-size: 1rem;
            font-family: inherit;
            transition: all 0.3s ease;
            background: var(--white);
        }

        .form-group input:focus,
        .form-group textarea:focus,
        .form-group select:focus {
            outline: none;
            border-color: var(--primary-teal);
            box-shadow: 0 0 0 3px rgba(33, 141, 141, 0.1);
        }

        .form-group textarea {
            resize: vertical;
            min-height: 120px;
        }

        .submit-button {
            width: 100%;
            padding: 1.2rem;
            background: var(--primary-teal);
            color: var(--white);
            border: none;
            border-radius: 8px;
            font-size: 1.1rem;
            font-weight: 600;
            cursor: pointer;
            transition: all 0.3s ease;
        }

        .submit-button:hover {
            background: #1a7070;
            transform: translateY(-2px);
            box-shadow: 0 5px 20px rgba(33, 141, 141, 0.3);
        }

        /* Footer */
        footer {
            background: var(--dark-charcoal);
            color: var(--white);
            padding: 3rem 2rem 1rem;
        }

        .footer-content {
            max-width: 1400px;
            margin: 0 auto;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 3rem;
            margin-bottom: 2rem;
        }

        .footer-section h4 {
            font-size: 1.3rem;
            margin-bottom: 1rem;
        }

        .footer-section p,
        .footer-section a {
            color: rgba(255, 255, 255, 0.8);
            font-size: 0.95rem;
            line-height: 1.8;
            text-decoration: none;
            display: block;
            margin-bottom: 0.5rem;
        }

        .footer-section a:hover {
            color: var(--primary-teal);
        }

        .footer-bottom {
            text-align: center;
            padding-top: 2rem;
            border-top: 1px solid rgba(255, 255, 255, 0.1);
            color: rgba(255, 255, 255, 0.6);
            font-size: 0.9rem;
        }

        /* Responsive Design */
        @media (max-width: 1024px) {
            .hero-content {
                grid-template-columns: 1fr;
                text-align: center;
            }

            .hero-text h1 {
                font-size: 2.5rem;
            }

            .slideshow-container {
                margin: 0 auto;
            }

            .nav-links {
                display: none;
            }

            .mobile-menu {
                display: flex;
            }

            .contact-container {
                grid-template-columns: 1fr;
            }

            .model-container {
                grid-template-columns: 1fr;
            }

            .journey-flow {
                flex-direction: column;
            }

            .journey-step::after {
                content: '↓';
                right: auto;
                bottom: -2rem;
                top: auto;
            }
        }

        @media (max-width: 768px) {
            .hero-text h1 {
                font-size: 2rem;
            }

            .hero-text .tagline {
                font-size: 1.2rem;
            }

            .section-header h2 {
                font-size: 2rem;
            }

            .service-grid,
            .value-grid,
            .case-study-grid {
                grid-template-columns: 1fr;
            }

            .value-card,
            .service-card {
                padding: 2rem;
            }

            section {
                padding: 4rem 1.5rem;
            }
        }

        /* Animations */
        @keyframes float {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-20px); }
        }

        .floating {
            animation: float 3s ease-in-out infinite;
        }

        /* Success Message */
        .success-message {
            display: none;
            background: var(--primary-teal);
            color: var(--white);
            padding: 1rem;
            border-radius: 8px;
            margin-top: 1rem;
            text-align: center;
        }

        .success-message.show {
            display: block;
            animation: fadeIn 0.5s ease-in-out;
        }
    </style>
</head>
<body>
    <!-- Navigation -->
    <nav class="navbar" id="navbar">
        <div class="nav-container">
            <div class="logo-container">
                <img src="https://agi-prod-file-upload-public-main-use1.s3.amazonaws.com/da210446-e67f-47cf-a5f4-92d49021d478" alt="Otocinclus Technology Logo" class="logo">
            </div>
            <ul class="nav-links">
                <li><a href="#home">Home</a></li>
                <li><a href="#value">Why Us</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#models">Engagement Models</a></li>
                <li><a href="#recruitment">Recruitment</a></li>
                <li><a href="#case-studies">Case Studies</a></li>
                <li><a href="#contact" class="cta-button">Get Started</a></li>
            </ul>
            <div class="mobile-menu" id="mobileMenu">
                <span></span>
                <span></span>
                <span></span>
            </div>
        </div>
    </nav>

    <!-- Hero Section with Slideshow -->
    <section class="hero" id="home">
        <div class="hero-content">
            <div class="hero-text">
                <p class="tagline">HR Consultancy &amp; HRMS Implementation Partner</p>
                <h1>Build Your Business.<br>We'll Build the Infrastructure.</h1>
                <p>Audit. Advise. Implement. Transfer. Your trusted partner for integrated HR solutions that liberate founders from administrative chaos.</p>
                <div class="hero-buttons">
                    <a href="#contact" class="btn-primary">Schedule Free Audit</a>
                    <a href="#services" class="btn-secondary">Explore Services</a>
                </div>
            </div>
            <div class="slideshow-container">
                <div class="slide active">
                    <div class="value-card">
                        <div class="value-icon">🔓</div>
                        <h2>We Remove the Admin Trap</h2>
                        <p>Founders spend 15-25 hours/week on HR admin. That's 25% of strategic capacity wasted.</p>
                        <ul>
                            <li>Zero compliance risk</li>
                            <li>20+ hours reclaimed monthly</li>
                            <li>40-60% cost savings vs internal HR</li>
                            <li>Single point of accountability</li>
                        </ul>
                    </div>
                </div>
                <div class="slide">
                    <div class="value-card">
                        <div class="value-icon">💰</div>
                        <h2>Flat Recruitment Fee</h2>
                        <p class="percentage">7%</p>
                        <p>No leadership penalty. One flat rate for all levels - junior to C-suite.</p>
                        <ul>
                            <li>30-65% savings on senior hires</li>
                            <li>90-day replacement guarantee</li>
                            <li>28-day average time-to-hire</li>
                            <li>Full recruitment lifecycle</li>
                        </ul>
                    </div>
                </div>
                <div class="slide-dots">
                    <span class="dot active" onclick="currentSlide(1)"></span>
                    <span class="dot" onclick="currentSlide(2)"></span>
                </div>
            </div>
        </div>
    </section>

    <!-- Value Proposition Section -->
    <section class="value-props" id="value">
        <div class="section-header">
            <h2>Why Otocinclus?</h2>
            <p>We're not just another HR vendor. We're your integrated infrastructure partner with a clear exit strategy.</p>
        </div>
        <div class="value-grid">
            <div class="value-item">
                <div class="value-item-icon">🎯</div>
                <h3>Complete HR Setup</h3>
                <p>Unlike traditional outsourcing or HRMS vendors that leave you to figure things out, we deliver end-to-end HR infrastructure - from policies to payroll to people management.</p>
            </div>
            <div class="value-item">
                <div class="value-item-icon">🔧</div>
                <h3>Vendor-Agnostic HRMS</h3>
                <p>We work with all major HRMS platforms (Keka, GreytHR, Zoho, Darwinbox). You get unbiased selection, expert implementation, and ongoing support - no vendor lock-in.</p>
            </div>
            <div class="value-item">
                <div class="value-item-icon">📊</div>
                <h3>Transparent Pricing</h3>
                <p>Flat 7% recruitment across all levels. Per-employee monthly subscriptions. No hidden costs, no tiered penalties. Priced at 40-60% of internal HR team costs.</p>
            </div>
            <div class="value-item">
                <div class="value-item-icon">🚀</div>
                <h3>Build-Operate-Transfer Model</h3>
                <p>Unlike competitors who create dependency, we build your HR function with a clear handover plan. You eventually own the infrastructure we create.</p>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section class="services" id="services">
        <div class="section-header">
            <h2>Comprehensive Service Portfolio</h2>
            <p>Full-stack HR infrastructure designed for growing businesses</p>
        </div>
        
        <div class="service-tabs">
            <button class="tab-button active" onclick="showService('governance')">HR Governance</button>
            <button class="tab-button" onclick="showService('hrms')">HRMS Implementation</button>
            <button class="tab-button" onclick="showService('payroll')">Payroll &amp; Compliance</button>
            <button class="tab-button" onclick="showService('attendance')">Attendance &amp; Leave</button>
            <button class="tab-button" onclick="showService('lifecycle')">Employee Lifecycle</button>
            <button class="tab-button" onclick="showService('recruitment')">Recruitment</button>
            <button class="tab-button" onclick="showService('training')">Training &amp; Handover</button>
        </div>

        <div id="governance" class="service-content active">
            <div class="service-grid">
                <div class="service-card">
                    <h3>HR Governance &amp; Policy Design</h3>
                    <ul>
                        <li>Comprehensive HR policy &amp; employee handbook creation</li>
                        <li>Organizational structure design &amp; role definitions</li>
                        <li>HR process mapping and documentation (SOPs)</li>
                        <li>Compliance framework setup (PF, ESI, PT, labour laws)</li>
                        <li>Shops &amp; Establishments Act compliance</li>
                        <li>Policy updates aligned with New Social Security Code</li>
                    </ul>
                </div>
            </div>
        </div>

        <div id="hrms" class="service-content">
            <div class="service-grid">
                <div class="service-card">
                    <h3>HRMS Selection &amp; Advisory</h3>
                    <ul>
                        <li>Vendor-agnostic HRMS selection &amp; fitment advisory</li>
                        <li>Requirements gathering &amp; evaluation</li>
                        <li>Platform comparison (Keka, GreytHR, Zoho, Darwinbox)</li>
                        <li>Cost-benefit analysis &amp; recommendation</li>
                    </ul>
                </div>
                <div class="service-card">
                    <h3>HRMS Configuration &amp; Setup</h3>
                    <ul>
                        <li>Employee master data and org structure setup</li>
                        <li>Payroll structures, salary components &amp; CTC models</li>
                        <li>Attendance, shift rules &amp; leave policies configuration</li>
                        <li>Statutory compliance setups within HRMS</li>
                        <li>Workflow automation &amp; approval hierarchies</li>
                    </ul>
                </div>
                <div class="service-card">
                    <h3>Data Migration &amp; Ongoing Support</h3>
                    <ul>
                        <li>Data migration from spreadsheets/legacy systems</li>
                        <li>Data cleansing &amp; validation</li>
                        <li>Ongoing HRMS administration &amp; support</li>
                        <li>System upgrades &amp; optimization</li>
                        <li>HRMS training for HR teams (Model 2 handover)</li>
                    </ul>
                </div>
            </div>
        </div>

        <div id="payroll" class="service-content">
            <div class="service-grid">
                <div class="service-card">
                    <h3>Payroll Administration</h3>
                    <ul>
                        <li>Monthly payroll processing (salaries, reimbursements, arrears)</li>
                        <li>Payslip generation &amp; distribution via ESS portals</li>
                        <li>Statutory deductions management (PF, ESI, PT, TDS)</li>
                        <li>Arrears calculation &amp; adjustments</li>
                        <li>Payroll MIS &amp; analytics reports</li>
                        <li>99.5% accuracy with Maker-Checker-Reviewer systems</li>
                    </ul>
                </div>
                <div class="service-card">
                    <h3>Statutory Compliance Shield</h3>
                    <ul>
                        <li>PF, ESI, PT filings &amp; challans</li>
                        <li>TDS compliance (Form 24Q, Form 16)</li>
                        <li>Statutory returns &amp; government reporting</li>
                        <li>Labour law adherence &amp; audit support</li>
                        <li>Compliance calendar with 7-day advance alerts</li>
                        <li>Professional Indemnity Insurance coverage</li>
                    </ul>
                </div>
                <div class="service-card">
                    <h3>Settlements &amp; MIS</h3>
                    <ul>
                        <li>Full &amp; final settlements (45-60 day SLA)</li>
                        <li>Related compliance documentation</li>
                        <li>Monthly payroll analytics &amp; dashboards</li>
                        <li>Cost center analysis &amp; reporting</li>
                        <li>Budget variance tracking</li>
                    </ul>
                </div>
            </div>
        </div>

        <div id="attendance" class="service-content">
            <div class="service-grid">
                <div class="service-card">
                    <h3>Attendance &amp; Time Management</h3>
                    <ul>
                        <li>Shift rules design &amp; configuration</li>
                        <li>Attendance logic setup &amp; automation</li>
                        <li>Biometric integration &amp; device management</li>
                        <li>Monthly attendance reconciliation</li>
                        <li>Real-time attendance dashboards</li>
                    </ul>
                </div>
                <div class="service-card">
                    <h3>Leave Management</h3>
                    <ul>
                        <li>Leave policy design &amp; setup</li>
                        <li>Leave accrual &amp; carry-forward rules</li>
                        <li>Leave tracking &amp; approval workflows</li>
                        <li>Leave balance monitoring &amp; reports</li>
                        <li>Integration with attendance &amp; payroll</li>
                    </ul>
                </div>
            </div>
        </div>

        <div id="lifecycle" class="service-content">
            <div class="service-grid">
                <div class="service-card">
                    <h3>Onboarding &amp; Documentation</h3>
                    <ul>
                        <li>End-to-end onboarding coordination</li>
                        <li>Documentation &amp; KYC management</li>
                        <li>HRMS account creation &amp; access setup</li>
                        <li>Background verification coordination</li>
                        <li>New hire orientation support</li>
                    </ul>
                </div>
                <div class="service-card">
                    <h3>Employee Records &amp; Lifecycle</h3>
                    <ul>
                        <li>Digital employee records management</li>
                        <li>Confirmation &amp; probation tracking</li>
                        <li>Appraisal cycle coordination (light PMS support)</li>
                        <li>Promotion &amp; transfer processing</li>
                        <li>Role-based data security &amp; permissions</li>
                    </ul>
                </div>
                <div class="service-card">
                    <h3>Exit Management</h3>
                    <ul>
                        <li>Exit process coordination</li>
                        <li>NOC &amp; clearance management</li>
                        <li>Asset recovery coordination</li>
                        <li>Full &amp; final settlement processing</li>
                        <li>Exit interview support (optional)</li>
                    </ul>
                </div>
            </div>
        </div>

        <div id="recruitment" class="service-content">
            <div class="service-grid">
                <div class="service-card">
                    <h3>Recruitment Services - Flat 7%</h3>
                    <ul>
                        <li>Requirement understanding &amp; manpower planning</li>
                        <li>JD creation &amp; role benchmarking</li>
                        <li>Multi-channel sourcing (job boards, LinkedIn, referrals)</li>
                        <li>Resume screening &amp; candidate evaluation</li>
                        <li>Interview coordination with hiring managers</li>
                        <li>Offer negotiation support</li>
                        <li>Joining &amp; onboarding coordination</li>
                        <li>90-day free replacement guarantee</li>
                    </ul>
                </div>
                <div class="service-card">
                    <h3>Recruitment Value Proposition</h3>
                    <ul>
                        <li><strong>Flat 7% of annual CTC - All levels</strong></li>
                        <li>No leadership penalty (traditional agencies charge 20%+)</li>
                        <li>30-65% savings on senior hires</li>
                        <li>28-day average time-to-hire (vs 45 days market average)</li>
                        <li>Retainer or success-based engagement options</li>
                        <li>Background checks &amp; reference verification (optional)</li>
                        <li>Recruitment continues even after HR handover (Model 2)</li>
                    </ul>
                </div>
            </div>
        </div>

        <div id="training" class="service-content">
            <div class="service-grid">
                <div class="service-card">
                    <h3>Capability Building &amp; Handover</h3>
                    <ul>
                        <li>HRMS administration training for internal HR</li>
                        <li>Payroll &amp; compliance training sessions</li>
                        <li>Process walkthroughs with SOP handover</li>
                        <li>Knowledge transfer for HR and finance teams</li>
                        <li>Post-handover support (as required)</li>
                        <li>Quarterly refresher training options</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- Engagement Models -->
    <section class="models" id="models">
        <div class="section-header">
            <h2>Flexible Engagement Models</h2>
            <p>Choose the partnership model that fits your growth stage</p>
        </div>
        <div class="model-container">
            <div class="model-card">
                <span class="model-badge">MODEL 1</span>
                <h3>Complete Outsourced HR Services</h3>
                <p class="subtitle">Best for companies who want us to handle everything</p>
                <p>We act as your extended HR department and manage all HR operations on your behalf. Perfect for 15-100 employee companies that need professional HR without building an internal team.</p>
                <div class="model-phases">
                    <div class="phase">
                        <h4>HR Policy &amp; Process Setup</h4>
                        <ul>
                            <li>HR policies &amp; employee handbook</li>
                            <li>Organizational structure &amp; role definitions</li>
                            <li>HR process mapping &amp; documentation</li>
                            <li>Compliance framework (PF, ESI, PT, Labour laws)</li>
                        </ul>
                    </div>
                    <div class="phase">
                        <h4>HRMS Implementation &amp; Management</h4>
                        <ul>
                            <li>HRMS selection support</li>
                            <li>Complete system configuration</li>
                            <li>Employee master data setup</li>
                            <li>Ongoing HRMS administration &amp; support</li>
                        </ul>
                    </div>
                    <div class="phase">
                        <h4>Ongoing Operations</h4>
                        <ul>
                            <li>Monthly payroll processing &amp; compliance</li>
                            <li>Attendance &amp; leave management</li>
                            <li>Employee lifecycle support</li>
                            <li>Continuous compliance assurance</li>
                        </ul>
                    </div>
                </div>
                <p style="margin-top: 2rem; font-weight: 600; color: var(--primary-teal);">Pricing: Per-employee monthly subscription</p>
            </div>

            <div class="model-card">
                <span class="model-badge">MODEL 2</span>
                <h3>HR Setup + Transition to Client Team</h3>
                <p class="subtitle">Best for companies planning to build an internal HR team</p>
                <p>We set up your entire HR framework, run operations initially, and then handover to your HR team after stabilization (2-3 months). Perfect for 50-250 employee growth-stage companies.</p>
                <div class="model-phases">
                    <div class="phase">
                        <h4>Phase 1: HR Setup &amp; HRMS Implementation (3-6 months)</h4>
                        <ul>
                            <li>HR policy &amp; handbook creation</li>
                            <li>Compliance &amp; statutory setup</li>
                            <li>HRMS implementation &amp; configuration</li>
                            <li>Payroll, attendance &amp; leave setup</li>
                            <li>Employee data migration</li>
                            <li>Process documentation (SOPs)</li>
                        </ul>
                    </div>
                    <div class="phase">
                        <h4>Phase 2: Initial HR Operations (12-18 months)</h4>
                        <ul>
                            <li>Payroll processing &amp; compliance filings</li>
                            <li>Attendance &amp; leave administration</li>
                            <li>Employee lifecycle support</li>
                            <li>HRMS monitoring &amp; fine-tuning</li>
                            <li>Issue resolution &amp; process stabilization</li>
                        </ul>
                    </div>
                    <div class="phase">
                        <h4>Phase 3: Training &amp; Handover (3 months)</h4>
                        <ul>
                            <li>HRMS training for internal HR</li>
                            <li>Payroll &amp; compliance training</li>
                            <li>Process walkthroughs &amp; SOP handover</li>
                            <li>Knowledge transfer sessions</li>
                            <li>Post-handover support (as required)</li>
                        </ul>
                    </div>
                </div>
                <p style="margin-top: 2rem; font-weight: 600; color: var(--primary-teal);">Pricing: Setup fees + Monthly subscription during operations</p>
            </div>
        </div>
        <div style="text-align: center; margin-top: 3rem; padding: 2rem; background: var(--white); border-radius: 15px;">
            <h3 style="color: var(--primary-teal); margin-bottom: 1rem;">Recruitment Services Available with Both Models</h3>
            <p style="color: var(--gray-text); font-size: 1.1rem;">Flat 7% recruitment can be added to either engagement model and continues even after HR handover in Model 2</p>
        </div>
    </section>

    <!-- Recruitment Highlight -->
    <section class="recruitment" id="recruitment">
        <div class="section-header">
            <h2>Recruitment That Doesn't Punish Growth</h2>
            <p>Eliminating the "Leadership Penalty" - One flat rate for all hiring levels</p>
        </div>
        <div class="pricing-comparison">
            <div class="pricing-card">
                <h3>Traditional Agencies</h3>
                <div class="price">8-20%</div>
                <p>Tiered pricing that increases with seniority</p>
                <ul>
                    <li>Junior roles: 8.33%</li>
                    <li>Mid-level roles: 12-15%</li>
                    <li>Senior roles: 20%+</li>
                    <li>Hidden costs &amp; dependencies</li>
                </ul>
            </div>
            <div class="pricing-card highlighted">
                <h3>Otocinclus Advantage</h3>
                <div class="price">7%</div>
                <p>One flat rate. All levels. No exceptions.</p>
                <ul>
                    <li>Junior to C-suite: Flat 7%</li>
                    <li>30-65% savings on senior hires</li>
                    <li>90-day replacement guarantee</li>
                    <li>28-day average time-to-hire</li>
                    <li>Full recruitment lifecycle</li>
                    <li>Background &amp; reference checks</li>
                </ul>
            </div>
            <div class="pricing-card">
                <h3>Your Savings</h3>
                <div class="price">30-65%</div>
                <p>Cost savings compared to traditional agencies</p>
                <ul>
                    <li>No leadership penalty</li>
                    <li>Transparent pricing</li>
                    <li>No hidden costs</li>
                    <li>Faster turnaround</li>
                </ul>
            </div>
        </div>
    </section>

    <!-- Customer Journey -->
    <section class="journey" id="journey">
        <div class="section-header">
            <h2>Your Journey With Us</h2>
            <p>From audit to complete HR infrastructure in weeks, not months</p>
        </div>
        <div class="journey-flow">
            <div class="journey-step">
                <div class="journey-icon">🔍</div>
                <h4>1. Audit</h4>
                <p>Free HR infrastructure audit to identify gaps and compliance risks</p>
            </div>
            <div class="journey-step">
                <div class="journey-icon">💡</div>
                <h4>2. Advise</h4>
                <p>Tailored recommendations for HRMS, processes, and engagement model</p>
            </div>
            <div class="journey-step">
                <div class="journey-icon">⚙️</div>
                <h4>3. Implement</h4>
                <p>Complete setup of policies, HRMS, payroll, and compliance framework</p>
            </div>
            <div class="journey-step">
                <div class="journey-icon">📈</div>
                <h4>4. Operate</h4>
                <p>Ongoing HR operations management with continuous optimization</p>
            </div>
            <div class="journey-step">
                <div class="journey-icon">🎓</div>
                <h4>5. Transfer (Optional)</h4>
                <p>Knowledge transfer and handover to your internal HR team</p>
            </div>
        </div>
    </section>

    <!-- Case Studies -->
    <section class="case-studies" id="case-studies">
        <div class="section-header">
            <h2>Success Stories</h2>
            <p>Real results from companies that trusted us with their HR infrastructure</p>
        </div>
        <div class="case-study-grid">
            <div class="case-study">
                <div class="case-study-header">
                    <div class="case-study-icon">🚀</div>
                    <div>
                        <h3>Tech Startup Scale-Up</h3>
                        <p class="industry">SaaS Technology | 45 Employees</p>
                    </div>
                </div>
                <p><strong>Challenge:</strong> Fast-growing startup spending 20+ hours/week on HR admin with spreadsheet-based processes and multiple compliance gaps.</p>
                <p><strong>Solution:</strong> Model 1 - Complete outsourced HR with Keka HRMS implementation, automated payroll, and integrated compliance framework.</p>
                <div class="case-study-results">
                    <div class="result-stat">
                        <div class="number">20+</div>
                        <div class="label">Hours Saved/Week</div>
                    </div>
                    <div class="result-stat">
                        <div class="number">100%</div>
                        <div class="label">Compliance</div>
                    </div>
                    <div class="result-stat">
                        <div class="number">45%</div>
                        <div class="label">Cost Savings</div>
                    </div>
                </div>
            </div>

            <div class="case-study">
                <div class="case-study-header">
                    <div class="case-study-icon">🏭</div>
                    <div>
                        <h3>Manufacturing Firm Transition</h3>
                        <p class="industry">Manufacturing | 120 Employees</p>
                    </div>
                </div>
                <p><strong>Challenge:</strong> Growing manufacturer needed to transition from manual processes to professional HR infrastructure before building internal team.</p>
                <p><strong>Solution:</strong> Model 2 - Build-Operate-Transfer with GreytHR implementation, 18-month operations, and complete handover to new HR manager.</p>
                <div class="case-study-results">
                    <div class="result-stat">
                        <div class="number">18 Mo</div>
                        <div class="label">To Independence</div>
                    </div>
                    <div class="result-stat">
                        <div class="number">Zero</div>
                        <div class="label">Payroll Errors</div>
                    </div>
                    <div class="result-stat">
                        <div class="number">50%</div>
                        <div class="label">Cost vs Hiring</div>
                    </div>
                </div>
            </div>

            <div class="case-study">
                <div class="case-study-header">
                    <div class="case-study-icon">🏢</div>
                    <div>
                        <h3>Services Company Recruitment</h3>
                        <p class="industry">Professional Services | 85 Employees</p>
                    </div>
                </div>
                <p><strong>Challenge:</strong> Consulting firm paying 15-20% recruitment fees to multiple agencies for different levels, resulting in high acquisition costs.</p>
                <p><strong>Solution:</strong> Flat 7% recruitment model across all levels with integrated onboarding, saving 35-55% on hiring costs.</p>
                <div class="case-study-results">
                    <div class="result-stat">
                        <div class="number">45%</div>
                        <div class="label">Recruitment Savings</div>
                    </div>
                    <div class="result-stat">
                        <div class="number">28 Days</div>
                        <div class="label">Avg Time-to-Hire</div>
                    </div>
                    <div class="result-stat">
                        <div class="number">35</div>
                        <div class="label">Hires in 12 Mo</div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section class="contact" id="contact">
        <div class="section-header">
            <h2>Let's Build Your HR Infrastructure</h2>
            <p>Schedule a free audit and discover how we can liberate you from the admin trap</p>
        </div>
        <div class="contact-container">
            <div class="contact-info">
                <h3>Get In Touch</h3>
                <div class="contact-item">
                    <div class="contact-icon">📍</div>
                    <div>
                        <h4>Address</h4>
                        <p>#124, Aratt Vivera, Begur<br>Bangalore - 560068<br>Karnataka, India</p>
                    </div>
                </div>
                <div class="contact-item">
                    <div class="contact-icon">📞</div>
                    <div>
                        <h4>Phone</h4>
                        <p>+91 [Your Phone Number]</p>
                    </div>
                </div>
                <div class="contact-item">
                    <div class="contact-icon">✉️</div>
                    <div>
                        <h4>Email</h4>
                        <p>info@otocinclus.com</p>
                    </div>
                </div>
                <div class="contact-item">
                    <div class="contact-icon">🆔</div>
                    <div>
                        <h4>PAN</h4>
                        <p>AAJFO9445L</p>
                    </div>
                </div>
            </div>
            <div class="contact-form">
                <h3>Request Free HR Audit</h3>
                <form id="contactForm">
                    <div class="form-group">
                        <label for="name">Full Name *</label>
                        <input type="text" id="name" name="name" required>
                    </div>
                    <div class="form-group">
                        <label for="email">Email Address *</label>
                        <input type="email" id="email" name="email" required>
                    </div>
                    <div class="form-group">
                        <label for="phone">Phone Number *</label>
                        <input type="tel" id="phone" name="phone" required>
                    </div>
                    <div class="form-group">
                        <label for="company">Company Name *</label>
                        <input type="text" id="company" name="company" required>
                    </div>
                    <div class="form-group">
                        <label for="employees">Number of Employees *</label>
                        <select id="employees" name="employees" required>
                            <option value="">Select range</option>
                            <option value="1-15">1-15 employees</option>
                            <option value="15-50">15-50 employees</option>
                            <option value="50-100">50-100 employees</option>
                            <option value="100-250">100-250 employees</option>
                            <option value="250+">250+ employees</option>
                        </select>
                    </div>
                    <div class="form-group">
                        <label for="interest">What are you interested in? *</label>
                        <select id="interest" name="interest" required>
                            <option value="">Select service</option>
                            <option value="model1">Complete Outsourced HR (Model 1)</option>
                            <option value="model2">HR Setup + Transfer (Model 2)</option>
                            <option value="recruitment">Recruitment Services (7%)</option>
                            <option value="hrms">HRMS Implementation Only</option>
                            <option value="audit">Free HR Audit First</option>
                        </select>
                    </div>
                    <div class="form-group">
                        <label for="message">Tell us about your HR challenges</label>
                        <textarea id="message" name="message" rows="4"></textarea>
                    </div>
                    <button type="submit" class="submit-button">Schedule Free Audit</button>
                    <div class="success-message" id="successMessage">
                        ✓ Thank you! We'll contact you within 24 hours to schedule your free HR audit.
                    </div>
                </form>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="footer-content">
            <div class="footer-section">
                <h4>Otocinclus Technology</h4>
                <p>Your trusted HR Consultancy and HRMS Implementation Partner. We remove the admin trap and liberate founders from administrative chaos.</p>
                <p style="margin-top: 1rem;"><strong>PAN:</strong> AAJFO9445L</p>
            </div>
            <div class="footer-section">
                <h4>Services</h4>
                <a href="#services">HR Governance &amp; Policy</a>
                <a href="#services">HRMS Implementation</a>
                <a href="#services">Payroll &amp; Compliance</a>
                <a href="#services">Attendance &amp; Leave</a>
                <a href="#services">Employee Lifecycle</a>
                <a href="#recruitment">Recruitment (7%)</a>
            </div>
            <div class="footer-section">
                <h4>Engagement Models</h4>
                <a href="#models">Complete Outsourced HR</a>
                <a href="#models">Build-Operate-Transfer</a>
                <a href="#recruitment">Flat 7% Recruitment</a>
                <a href="#journey">Customer Journey</a>
                <a href="#case-studies">Case Studies</a>
            </div>
            <div class="footer-section">
                <h4>Company</h4>
                <a href="#value">Why Otocinclus</a>
                <a href="#contact">Contact Us</a>
                <a href="#contact">Free HR Audit</a>
                <p style="margin-top: 1rem;">📍 Bangalore, Karnataka</p>
            </div>
        </div>
        <div class="footer-bottom">
            <p>&copy; 2026 Otocinclus Technology. All rights reserved. | Audit. Advise. Implement. Transfer.</p>
        </div>
    </footer>

    <script>
        // Navbar scroll effect
        window.addEventListener('scroll', () => {
            const navbar = document.getElementById('navbar');
            if (window.scrollY > 50) {
                navbar.classList.add('scrolled');
            } else {
                navbar.classList.remove('scrolled');
            }
        });

        // Smooth scrolling
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    target.scrollIntoView({
                        behavior: 'smooth',
                        block: 'start'
                    });
                }
            });
        });

        // Slideshow functionality
        let slideIndex = 1;
        let slideTimer;

        function showSlides(n) {
            let slides = document.getElementsByClassName('slide');
            let dots = document.getElementsByClassName('dot');
            
            if (n > slides.length) { slideIndex = 1; }
            if (n < 1) { slideIndex = slides.length; }
            
            for (let i = 0; i < slides.length; i++) {
                slides[i].classList.remove('active');
            }
            for (let i = 0; i < dots.length; i++) {
                dots[i].classList.remove('active');
            }
            
            slides[slideIndex - 1].classList.add('active');
            dots[slideIndex - 1].classList.add('active');
        }

        function currentSlide(n) {
            clearInterval(slideTimer);
            slideIndex = n;
            showSlides(slideIndex);
            startSlideshow();
        }

        function nextSlide() {
            slideIndex++;
            showSlides(slideIndex);
        }

        function startSlideshow() {
            slideTimer = setInterval(nextSlide, 5000);
        }

        showSlides(slideIndex);
        startSlideshow();

        // Service tabs functionality
        function showService(serviceName) {
            const contents = document.querySelectorAll('.service-content');
            const buttons = document.querySelectorAll('.tab-button');
            
            contents.forEach(content => {
                content.classList.remove('active');
            });
            
            buttons.forEach(button => {
                button.classList.remove('active');
            });
            
            document.getElementById(serviceName).classList.add('active');
            event.target.classList.add('active');
        }

        // Form submission
        document.getElementById('contactForm').addEventListener('submit', function(e) {
            e.preventDefault();
            
            // In a real implementation, this would send data to a server
            const successMessage = document.getElementById('successMessage');
            successMessage.classList.add('show');
            
            // Reset form
            this.reset();
            
            // Hide success message after 5 seconds
            setTimeout(() => {
                successMessage.classList.remove('show');
            }, 5000);
        });

        // Mobile menu toggle (for future implementation)
        document.getElementById('mobileMenu').addEventListener('click', function() {
            alert('Mobile menu coming soon! For now, please scroll to navigate or use a desktop device.');
        });
    </script>
</body>
</html>

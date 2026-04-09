---
layout: nill
---

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Web Title</title>
</head>

<body itemscope itemtype="https://schema.org/WebPage" role="document">

    <header itemscope itemtype="https://schema.org/WPHeader" role="banner">
        <p>Header Content</p>
        <nav itemscope itemtype="https://schema.org/SiteNavigationElement" role="navigation">
            <a itemprop="url" href="/"><span itemprop="name">Home</span></a>
        </nav>
    </header>

    <main role="main" itemprop="mainContentOfPage">
        <section itemprop="mainEntity" itemscope itemtype="https://schema.org/SearchAction">
            <div itemprop="query-input" itemscope itemtype="https://schema.org/PropertyValueSpecification">
                <meta itemprop="valueName" content="q"/> 
                <input type="search" 
                       name="q" 
                       placeholder="Search" 
                       aria-label="Search" 
                       pattern=".{3,}" 
                       title="At least 3 characters" 
                       required>
            </div>
        </section>

        <p>Main content text goes here.</p>
        
    </main>

    <footer role="contentinfo" itemscope itemtype="https://schema.org/WPFooter">
        <p>Footer Content</p>
    </footer>

</body>
</html>

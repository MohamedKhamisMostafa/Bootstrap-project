# Mega-Courses-Website
![](https://github.com/MohamedKhamisMostafa/Bootstrap-project/blob/main/Screenshot%20-%20Mega%20Courses%20-.png)
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mega Courses</title>
    <link rel="stylesheet" href="css/bootstrap.min.css">
    <link rel="stylesheet" href="css/stayel.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link
        href="https://fonts.googleapis.com/css2?family=Lato:ital,wght@0,100;0,300;0,400;0,700;0,900;1,100;1,300;1,400;1,700;1,900&display=swap"
        rel="stylesheet">
</head>

<body>
    <!-- start navbar -->
    <nav class="navbar navbar-expand-lg bg-body-tertiary">
        <div class="container-fluid">
            <a class="navbar-brand" href="#">Mega</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse"
                data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false"
                aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                    <li class="nav-item">
                        <a class="nav-link active" aria-current="page" href="#">Courses</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">About</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Contact</a>
                    </li>

                </ul>
                <form class="d-flex" role="search">
                    <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
                    <button class="btn btn-outline-success" type="submit">Search</button>
                </form>
            </div>
        </div>
    </nav>
    <!-- end navbar -->

    <!-- start banner -->
    <div class="container py-5 border-bottom">
        <div class="row">
            <div class="col-6">
                <h1 class="banner-heading">Start</h1>
                <h1 class="banner-heading">Learning</h1>
                <h1 class="banner-heading">Now</h1>
                <p>Lorem, ipsum. ipsum. ipsum dolor sit., ipsum dolor sit ame Repellat, aliquid!, . Ullam unde nemo fuga
                    voluptates sunt? Quasi molestias nihil voluptates reprehenderit omnis.</p>
                <a class="btn btn-success" href="">Start Now</a>
            </div>
            <div class="col-3">
                <img class="img-fluid rounded" src="images/h5-rev-img-01.jpg" alt="">
            </div>
            <div class="col-3">
                <img class="img-fluid rounded" src="images/h5-rev-img-02.jpg" alt="">
            </div>
        </div>
    </div>
    <!-- end banner  -->

    <!-- start courses -->
    <div class="container py-5">
        <h4 class="fw-semibold">All You Nees To Master Coding</h4>
        <div class="row">
            <div class="col-4 my-2">
                <div class="shadow py-4 px-5 rounded">
                    <span>
                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor"
                            class="bi bi-fast-forward course-icon" viewBox="0 0 16 16">
                            <path
                                d="M6.804 8 1 4.633v6.734L6.804 8Zm.792-.696a.802.802 0 0 1 0 1.392l-6.363 3.692C.713 12.69 0 12.345 0 11.692V4.308c0-.653.713-.998 1.233-.696l6.363 3.692Z" />
                            <path
                                d="M14.804 8 9 4.633v6.734L14.804 8Zm.792-.696a.802.802 0 0 1 0 1.392l-6.363 3.692C8.713 12.69 8 12.345 8 11.692V4.308c0-.653.713-.998 1.233-.696l6.363 3.692Z" />
                        </svg>
                    </span>
                    <h4 class="mt-3">Learning Path</h4>
                    <p>Lorem, ipsum. ipsum. ipsum dolor sit amet consectetur adipisicing elit. Dolores veniam laudantium
                    </p>
                </div>
            </div>
            <div class="col-4 my-2">
                <div class="shadow py-4 px-5 rounded">
                    <span>
                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor"
                            class="bi bi-git course-icon" viewBox="0 0 16 16">
                            <path
                                d="M15.698 7.287 8.712.302a1.03 1.03 0 0 0-1.457 0l-1.45 1.45 1.84 1.84a1.223 1.223 0 0 1 1.55 1.56l1.773 1.774a1.224 1.224 0 0 1 1.267 2.025 1.226 1.226 0 0 1-2.002-1.334L8.58 5.963v4.353a1.226 1.226 0 1 1-1.008-.036V5.887a1.226 1.226 0 0 1-.666-1.608L5.093 2.465l-4.79 4.79a1.03 1.03 0 0 0 0 1.457l6.986 6.986a1.03 1.03 0 0 0 1.457 0l6.953-6.953a1.031 1.031 0 0 0 0-1.457" />
                        </svg>
                    </span>
                    <h4 class="mt-3">Learning Path</h4>
                    <p>Lorem, ipsum. ipsum dolor sit amet consectetur adipisicing elit. Dolores veniam laudantium </p>
                </div>
            </div>
            <div class="col-4 my-2">
                <div class="shadow py-4 px-5 rounded">
                    <span>
                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor"
                            class="bi bi-braces-asterisk course-icon " viewBox="0 0 16 16">
                            <path fill-rule="evenodd"
                                d="M1.114 8.063V7.9c1.005-.102 1.497-.615 1.497-1.6V4.503c0-1.094.39-1.538 1.354-1.538h.273V2h-.376C2.25 2 1.49 2.759 1.49 4.352v1.524c0 1.094-.376 1.456-1.49 1.456v1.299c1.114 0 1.49.362 1.49 1.456v1.524c0 1.593.759 2.352 2.372 2.352h.376v-.964h-.273c-.964 0-1.354-.444-1.354-1.538V9.663c0-.984-.492-1.497-1.497-1.6ZM14.886 7.9v.164c-1.005.103-1.497.616-1.497 1.6v1.798c0 1.094-.39 1.538-1.354 1.538h-.273v.964h.376c1.613 0 2.372-.759 2.372-2.352v-1.524c0-1.094.376-1.456 1.49-1.456v-1.3c-1.114 0-1.49-.362-1.49-1.456V4.352C14.51 2.759 13.75 2 12.138 2h-.376v.964h.273c.964 0 1.354.444 1.354 1.538V6.3c0 .984.492 1.497 1.497 1.6ZM7.5 11.5V9.207l-1.621 1.621-.707-.707L6.792 8.5H4.5v-1h2.293L5.172 5.879l.707-.707L7.5 6.792V4.5h1v2.293l1.621-1.621.707.707L9.208 7.5H11.5v1H9.207l1.621 1.621-.707.707L8.5 9.208V11.5h-1Z" />
                        </svg>
                    </span>
                    <h4 class="mt-3">Learning Path</h4>
                    <p>Lorem, ipsum. ipsum dolor sit amet consectetur adipisicing elit. Dolores veniam laudantium </p>
                </div>


            </div>
            <div class="col-4 my-2">
                <div class="shadow py-4 px-5 rounded">
                    <span>
                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor"
                            class="bi bi-fast-forward course-icon" viewBox="0 0 16 16">
                            <path
                                d="M6.804 8 1 4.633v6.734L6.804 8Zm.792-.696a.802.802 0 0 1 0 1.392l-6.363 3.692C.713 12.69 0 12.345 0 11.692V4.308c0-.653.713-.998 1.233-.696l6.363 3.692Z" />
                            <path
                                d="M14.804 8 9 4.633v6.734L14.804 8Zm.792-.696a.802.802 0 0 1 0 1.392l-6.363 3.692C8.713 12.69 8 12.345 8 11.692V4.308c0-.653.713-.998 1.233-.696l6.363 3.692Z" />
                        </svg>
                    </span>
                    <h4 class="mt-3">Learning Path</h4>
                    <p>Lorem, ipsum. ipsum. ipsum dolor sit amet consectetur adipisicing elit. Dolores veniam laudantium
                    </p>
                </div>


            </div>
            <div class="col-4 my-2">
                <div class="shadow py-4 px-5 rounded">
                    <span>
                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor"
                            class="bi bi-git course-icon" viewBox="0 0 16 16">
                            <path
                                d="M15.698 7.287 8.712.302a1.03 1.03 0 0 0-1.457 0l-1.45 1.45 1.84 1.84a1.223 1.223 0 0 1 1.55 1.56l1.773 1.774a1.224 1.224 0 0 1 1.267 2.025 1.226 1.226 0 0 1-2.002-1.334L8.58 5.963v4.353a1.226 1.226 0 1 1-1.008-.036V5.887a1.226 1.226 0 0 1-.666-1.608L5.093 2.465l-4.79 4.79a1.03 1.03 0 0 0 0 1.457l6.986 6.986a1.03 1.03 0 0 0 1.457 0l6.953-6.953a1.031 1.031 0 0 0 0-1.457" />
                        </svg>
                    </span>
                    <h4 class="mt-3">Learning Path</h4>
                    <p>Lorem, ipsum. ipsum dolor sit amet consectetur adipisicing elit. Dolores veniam laudantium </p>
                </div>
            </div>
            <div class="col-4 my-2">
                <div class="shadow py-4 px-5 rounded">
                    <span>
                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor"
                            class="bi bi-braces-asterisk course-icon " viewBox="0 0 16 16">
                            <path fill-rule="evenodd"
                                d="M1.114 8.063V7.9c1.005-.102 1.497-.615 1.497-1.6V4.503c0-1.094.39-1.538 1.354-1.538h.273V2h-.376C2.25 2 1.49 2.759 1.49 4.352v1.524c0 1.094-.376 1.456-1.49 1.456v1.299c1.114 0 1.49.362 1.49 1.456v1.524c0 1.593.759 2.352 2.372 2.352h.376v-.964h-.273c-.964 0-1.354-.444-1.354-1.538V9.663c0-.984-.492-1.497-1.497-1.6ZM14.886 7.9v.164c-1.005.103-1.497.616-1.497 1.6v1.798c0 1.094-.39 1.538-1.354 1.538h-.273v.964h.376c1.613 0 2.372-.759 2.372-2.352v-1.524c0-1.094.376-1.456 1.49-1.456v-1.3c-1.114 0-1.49-.362-1.49-1.456V4.352C14.51 2.759 13.75 2 12.138 2h-.376v.964h.273c.964 0 1.354.444 1.354 1.538V6.3c0 .984.492 1.497 1.497 1.6ZM7.5 11.5V9.207l-1.621 1.621-.707-.707L6.792 8.5H4.5v-1h2.293L5.172 5.879l.707-.707L7.5 6.792V4.5h1v2.293l1.621-1.621.707.707L9.208 7.5H11.5v1H9.207l1.621 1.621-.707.707L8.5 9.208V11.5h-1Z" />
                        </svg>
                    </span>
                    <h4 class="mt-3">Learning Path</h4>
                    <p>Lorem, ipsum. ipsum dolor sit amet consectetur adipisicing elit. Dolores veniam laudantium </p>
                </div>


            </div>            
        </div>

    </div>
    <div class="container pt-4 pb-5  border-bottom">
        <h4 class="fw-semibold">Learn a new skill</h4>
        <div class="row">
            <div class="col-2 my-2">
                <div class="shadow py-2 text-center rounded">
                    <span>
                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-github course-icon-sm  " viewBox="0 0 16 16">
                            <path d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.012 8.012 0 0 0 16 8c0-4.42-3.58-8-8-8z"/>
                          </svg>
                    </span>
                    <h5 class="mt-3">Git & Github</h5>
                </div>
            </div>
            <div class="col-2 my-2">
                <div class="shadow py-2 text-center rounded ">
                    <img class="img-icon" src="images/pngwing.com__1_.png" alt="">

                    <h5 class="mt-3">Dijango</h5>
                </div>
            </div>            
            <div class="col-2 my-2">
                <div class="shadow py-2 text-center rounded ">
                    <img class="img-icon" src="images/Untitled-removebg-preview.png" alt="">

                    <h5 class="mt-3">Anaconda</h5>
                </div>
            </div>
            <div class="col-2 my-2 rounded ">
                <div class="shadow py-2 text-center ">
                    <img class="img-icon" src="images/pngwing.com.png" alt="">

                    <h5 class="mt-3">Python</h5>
                </div>
            </div>
            <div class="col-2 my-2 ">
                <div class="shadow py-2 text-center rounded ">
                    <img class="img-icon" src="images/pngegg.png" alt="">

                    <h5 class="mt-3">API</h5>
                </div>
            </div>
            <div class="col-2 my-2">
                <div class="shadow py-2 text-center rounded">
                    <img class="img-icon" src="images/SeekPng.com_analytics-icon-png_1386076.png" alt="">

                    
                    <h5 class="mt-3">Data Analysis</h5>
                </div>
            </div>                                    
        </div>
    </div>
    <!-- end courses -->

    <!--star features -->
    <div class="container py-5 ">
        <h4 class="fw-semibold">Why Us ?</h4>
        <div class="row">
            <div class="col-5">
                <div class="mt-4">
                    <div class="accordion accordion-flush" id="accordionFlushExample">
                        <div class="accordion-item">
                          <h2 class="accordion-header">
                            <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#flush-collapseOne" aria-expanded="false" aria-controls="flush-collapseOne">
                              Accordion Item #1
                            </button>
                          </h2>
                          <div id="flush-collapseOne" class="accordion-collapse " data-bs-parent="#accordionFlushExample">
                            <div class="accordion-body">Placeholder content for this accordion, which is intended to demonstrate thePlaceholder content for this accordion, which is intended to demonstrate the Placeholder content for this accordion, which is intended to demonstrate the class. This is the first item's accordion body.</div>
                          </div>
                        </div>
                        <div class="accordion-item">
                          <h2 class="accordion-header">
                            <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#flush-collapseTwo" aria-expanded="false" aria-controls="flush-collapseTwo">
                              Accordion Item #2
                            </button>
                          </h2>
                          <div id="flush-collapseTwo" class="accordion-collapse collapse" data-bs-parent="#accordionFlushExample">
                            <div class="accordion-body">Placeholder content for this accordion, which is intended to demonstrate the <code>.accordion-flush</code> class. This is the second item's accordion body. Let's imagine this being filled with some actual content.</div>
                          </div>
                        </div>
                        <div class="accordion-item">
                          <h2 class="accordion-header">
                            <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#flush-collapseThree" aria-expanded="false" aria-controls="flush-collapseThree">
                              Accordion Item #3
                            </button>
                          </h2>
                          <div id="flush-collapseThree" class="accordion-collapse collapse" data-bs-parent="#accordionFlushExample">
                            <div class="accordion-body">Placeholder content for this accordion, which is intended to demonstrate the <code>.accordion-flush</code> class. This is the third item's accordion body. Nothing more exciting happening here in terms of content, but just filling up the space to make it look, at least at first glance, a bit more representative of how this would look in a real-world application.</div>
                          </div>
                        </div>
                      </div>
                </div>

            </div>
            <div class="col-2">
            </div>
            <div class="col-5">
                <div>
                    <img class="img-fluid rounded " src="images/features1.jpg" alt="">
                </div>
            </div>
        </div>
    </div>

    <!-- end features -->
    <script src="js/bootstrap.bundle.js"></script>
</body>

</html>

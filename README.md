# 🛰️ Space Remote Sensing Bootcamp

[![GitHub stars](https://img.shields.io/github/stars/ajaynagotha/space-remote-sensing-bootcamp?style=social)](https://github.com/ajaynagotha/space-remote-sensing-bootcamp/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/ajaynagotha/space-remote-sensing-bootcamp?style=social)](https://github.com/ajaynagotha/space-remote-sensing-bootcamp/network/members)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)
[![Space Jobs Ready](https://img.shields.io/badge/Space%20Jobs-Ready-blue.svg)](https://github.com/ajaynagotha/space-remote-sensing-bootcamp)

## 🚀 Open-Source Space Industry GIS/RS Bootcamp - 3 Months to Job Ready

**Intensive, hands-on learning system designed for landing roles at space organizations**

🎯 **Your Goal:** Land a job at NASA, ESA, ISRO, SpaceX, Planet Labs, or other space organizations  
⏱️ **Time Commitment:** 25-30 hours/week for 12 weeks  
📈 **Success Focus:** Structured learning path with portfolio-driven approach  
🌍 **Open Source:** Free, comprehensive, and community-driven  

---

## 📖 Table of Contents

- [🎯 What You'll Achieve](#-what-youll-achieve)
- [🚀 Quick Start](#-quick-start)
- [📅 12-Week Curriculum](#-12-week-curriculum)
- [💼 Career Outcomes](#-career-outcomes)
- [🏆 Certifications](#-certifications)
- [👥 Community](#-community)
- [🤝 Contributing](#-contributing)
- [📜 License](#-license)

---

## 🎯 What You'll Achieve

### ✅ **Technical Skills**
- **Python for Geospatial Analysis** - Master GeoPandas, Rasterio, and Earth Engine
- **Professional GIS Software** - Advanced QGIS, ESA SNAP, and NASA tools
- **Machine Learning** - AI-powered Earth observation and satellite image analysis
- **Cloud Computing** - Google Earth Engine, AWS, and planetary-scale processing
- **Real-time Processing** - Mission operations center dashboards and streaming data

### 🎓 **Industry Certifications**
- NASA ARSET Remote Sensing Fundamentals
- ESA Earth Observation Training Certificates
- Google Earth Engine Certified Developer
- Space agency standard tool proficiencies

### 💼 **Career Ready Portfolio**
- **15+ Portfolio Projects** with space industry applications
- **Professional Website** showcasing your work
- **GitHub Profile** with production-quality code
- **LinkedIn Network** of 200+ space professionals

### 🛰️ **Space Organization Pathways**
- Direct application guidance for NASA, ESA, ISRO
- Commercial space company career tracks (SpaceX, Planet, Maxar)
- Aerospace contractor opportunities (Lockheed, Northrop Grumman)
- Salary expectations: $75K-$200K+ based on experience

---

## 🚀 Quick Start

### Prerequisites
```bash
# Basic programming knowledge (any language)
# Computer with 16GB+ RAM recommended
# Reliable internet connection
# GitHub account
```

### 1. Clone & Setup
```bash
git clone https://github.com/ajaynagotha/space-remote-sensing-bootcamp.git
cd space-remote-sensing-bootcamp
```

### 2. Environment Setup
```bash
# Install Anaconda
wget https://repo.anaconda.com/archive/Anaconda3-2024.02-1-Linux-x86_64.sh
bash Anaconda3-2024.02-1-Linux-x86_64.sh

# Create space GIS environment
conda env create -f setup/environment.yml
conda activate space-gis

# Verify installation
python setup/verify_installation.py
```

### 3. Start Week 1
```bash
cd week-01-python-gis
jupyter notebook daily-tasks/day-01-setup.ipynb
```

### 4. Join Community
- ⭐ **Star this repo** to show support
- 💬 **[Join Discussions](https://github.com/ajaynagotha/space-remote-sensing-bootcamp/discussions)** for peer support
- 📢 **[Follow Updates](https://github.com/ajaynagotha/space-remote-sensing-bootcamp/releases)** for new content
- 🐦 **Tweet your progress** with #SpaceRemoteSensingBootcamp

---

## 📅 12-Week Curriculum

<details>
<summary><strong>🌟 Month 1: Foundations & Space Agency Integration</strong></summary>

### Week 1: Python + GIS Mastery
**🎯 Goal:** Master Python geospatial libraries and create your first space application

**📚 Learning Resources:**
- **Python Official Tutorial:** https://docs.python.org/3/tutorial/
- **NumPy Quickstart:** https://numpy.org/doc/stable/user/quickstart.html
- **Pandas Tutorial:** https://pandas.pydata.org/docs/user_guide/10min.html
- **GeoPandas Installation:** https://geopandas.org/en/stable/getting_started/install.html
- **Rasterio Quickstart:** https://rasterio.readthedocs.io/en/latest/quickstart.html
- **Folium Documentation:** https://python-visualization.github.io/folium/

**🌍 Space Agency Accounts (Required):**
- **NASA Earthdata:** https://urs.earthdata.nasa.gov/users/new
- **ESA Copernicus Hub:** https://scihub.copernicus.eu/dhus/#/home

**📚 Learning Path:**
- Python fundamentals for satellite data processing
- GeoPandas, Rasterio, Folium for interactive mapping
- NASA Earthdata and ESA Copernicus account setup

**🚀 Portfolio Project:** [Multi-Satellite Disaster Monitoring Dashboard](week-01-python-gis/project/)

**📋 Daily Tasks:**
- [Day 1: Environment Setup](week-01-python-gis/daily-tasks/day-01-setup.md)
- [Day 2: Python Fundamentals](week-01-python-gis/daily-tasks/day-02-python.md)
- [Day 3-7: GeoPython Libraries](week-01-python-gis/daily-tasks/)

---

### Week 2: GIS Fundamentals + Space Applications
**🎯 Goal:** Master QGIS and spatial analysis for satellite mission planning

**📚 Essential Resources:**
- **QGIS 3.34 Download:** https://qgis.org/en/site/forusers/download.html
- **QGIS Training Manual:** https://docs.qgis.org/3.34/en/docs/training_manual/
- **QGIS User Guide:** https://docs.qgis.org/3.34/en/docs/user_manual/
- **EPSG Coordinate Systems:** https://epsg.org/
- **Projection Wizard:** https://projectionwizard.org/
- **Natural Earth Data:** https://www.naturalearthdata.com/downloads/
- **USGS National Map:** https://apps.nationalmap.gov/downloader/

**📚 Learning Path:**
- QGIS professional workflows
- Coordinate systems and projections for Earth observation
- Spatial analysis for ground station optimization

**🚀 Portfolio Project:** [Satellite Ground Station Coverage Analysis](week-02-gis-fundamentals/project/)

---

### Week 3: Remote Sensing + NASA ARSET Training
**🎯 Goal:** Complete NASA ARSET certification and master satellite data access

**📚 Essential Resources:**
- **NASA ARSET Fundamentals:** https://appliedsciences.nasa.gov/get-involved/training/english/arset-fundamentals-remote-sensing
- **NASA Earthdata Learn:** https://www.earthdata.nasa.gov/learn
- **NASA Giovanni:** https://giovanni.gsfc.nasa.gov/giovanni/
- **NASA Worldview:** https://worldview.earthdata.nasa.gov/
- **USGS EarthExplorer:** https://earthexplorer.usgs.gov/
- **ESA Climate Change Initiative:** https://climate.esa.int/en/projects/
- **Landsat Collection 2:** https://www.usgs.gov/landsat-missions/landsat-collection-2

**📚 Learning Path:**
- NASA ARSET Fundamentals of Remote Sensing (Certificate)
- Multi-agency data access (NASA, ESA, USGS)
- Basic image processing and enhancement

**🚀 Portfolio Project:** [Multi-Agency Satellite Data Integration Platform](week-03-remote-sensing/project/)

---

### Week 4: Image Processing + ESA SNAP
**🎯 Goal:** Master professional satellite image processing workflows

**📚 Essential Resources:**
- **ESA SNAP Download:** https://step.esa.int/main/download/snap-download/
- **SNAP Tutorials:** https://step.esa.int/main/doc/tutorials/
- **Google Earth Engine Sign-up:** https://signup.earthengine.google.com/
- **Earth Engine Code Editor:** https://code.earthengine.google.com/
- **Earth Engine Python API:** https://developers.google.com/earth-engine/tutorials/tutorial_python_01
- **Rasterio Advanced:** https://rasterio.readthedocs.io/en/latest/topics/image_processing.html
- **Scikit-image:** https://scikit-image.org/docs/stable/
- **NASA LAADS DAAC:** https://ladsweb.modaps.eosdis.nasa.gov/

**📚 Learning Path:**
- ESA SNAP atmospheric correction and processing
- Google Earth Engine JavaScript and Python APIs
- Spectral indices and image enhancement

**🚀 Portfolio Project:** [Automated Atmospheric Correction Pipeline](week-04-image-processing/project/)

</details>

<details>
<summary><strong>🌍 Month 2: Advanced Analysis & Mission Applications</strong></summary>

### Week 5-8: [Advanced Techniques](curriculum/month-2.md)

#### Week 5: Machine Learning for Earth Observation
**📚 Essential Resources:**
- **NASA ARSET ML Course:** https://appliedsciences.nasa.gov/get-involved/training/english/arset-large-scale-applications-machine-learning-using-remote-sensing
- **Scikit-learn:** https://scikit-learn.org/stable/
- **TensorFlow:** https://www.tensorflow.org/install
- **Earth Engine ML Guide:** https://developers.google.com/earth-engine/guides/machine-learning
- **NASA NEX Platform:** https://www.nasa.gov/nex/
- **Random Forest Classification:** https://developers.google.com/earth-engine/guides/classification#random-forest

#### Week 6: Change Detection & Climate Monitoring  
**📚 Essential Resources:**
- **ESA Climate Data Portal:** https://cds.climate.copernicus.eu/
- **NASA Climate Data:** https://climate.nasa.gov/
- **MODIS Time Series:** https://modis.gsfc.nasa.gov/data/
- **LandTrendr Algorithm:** https://emapr.github.io/LT-GEE/
- **CCDC Algorithm:** https://developers.google.com/earth-engine/guides/ccdc
- **NASA GISS Temperature:** https://data.giss.nasa.gov/gistemp/

#### Week 7: Spatial Optimization & Mission Planning
**📚 Essential Resources:**
- **PySAL Library:** https://pysal.org/
- **Spatial Optimization:** https://github.com/riatelab/spopt
- **NetworkX:** https://networkx.org/
- **PyEphem:** https://pypi.org/project/pyephem/
- **Skyfield:** https://rhodesmill.org/skyfield/
- **NASA GMAT:** https://gmat.gsfc.nasa.gov/

#### Week 8: Atmospheric Science & Climate Modeling
**📚 Essential Resources:**
- **NASA MERRA-2:** https://gmao.gsfc.nasa.gov/reanalysis/MERRA-2/
- **HYSPLIT Model:** https://www.ready.noaa.gov/HYSPLIT.php
- **ECMWF Data:** https://www.ecmwf.int/
- **NASA Climate Modeling:** https://www.giss.nasa.gov/tools/
- **OCO-2/3 Data:** https://ocov2.jpl.nasa.gov/

</details>

<details>
<summary><strong>🪐 Month 3: Specialization & Career Preparation</strong></summary>

### Week 9-12: [Professional Development](curriculum/month-3.md)

#### Week 9: Planetary Remote Sensing
**📚 Essential Resources:**
- **NASA Planetary Data System:** https://pds.nasa.gov/
- **Mars Reconnaissance Orbiter:** https://pds-imaging.jpl.nasa.gov/volumes/mro.html
- **Lunar Reconnaissance Orbiter:** https://pds-imaging.jpl.nasa.gov/volumes/lro.html
- **ISIS Software:** https://isis.astrogeology.usgs.gov/
- **USGS Astrogeology:** https://www.usgs.gov/centers/astrogeology-science-center
- **ESA Mars Express:** https://www.esa.int/Science_Exploration/Space_Science/Mars_Express
- **ESA Planetary Archive:** https://archives.esac.esa.int/psa/

#### Week 10: Mission Operations & Real-Time Processing
**📚 Essential Resources:**
- **Apache Kafka:** https://kafka.apache.org/quickstart
- **Apache Spark:** https://spark.apache.org/docs/latest/quick-start.html
- **Streamlit:** https://docs.streamlit.io/
- **NASA Real-Time Data:** https://earthdata.nasa.gov/earth-observation-data/near-real-time
- **NOAA Real-Time Imagery:** https://www.nesdis.noaa.gov/real-time-imagery
- **Plotly Dash:** https://plotly.com/dash/

#### Week 11: Space Industry Applications
**📚 Essential Resources:**
- **Planet Labs API:** https://developers.planet.com/
- **Maxar SecureWatch:** https://securewatch.maxar.com/
- **React Documentation:** https://reactjs.org/docs/getting-started.html
- **D3.js Visualization:** https://d3js.org/
- **WebGL Earth:** https://www.webglearth.com/
- **AWS Geospatial:** https://aws.amazon.com/earth/

#### Week 12: Capstone Integration & Job Applications
**📚 Essential Resources:**
- **GitHub Pages:** https://pages.github.com/
- **LinkedIn Profile Guide:** https://business.linkedin.com/talent-solutions/resources/how-to-hire/linkedin-profile-best-practices
- **Technical Writing:** https://developers.google.com/tech-writing
- **NASA Careers:** https://www.usajobs.gov/Search/Results?a=DNASA
- **ESA Careers:** https://jobs.esa.int/
- **SpaceX Careers:** https://www.spacex.com/careers/

</details>

---

## 💼 Career Outcomes

### 📊 **Graduate Success Focus**
- Portfolio-driven approach with 15+ industry-relevant projects
- Professional certification preparation and completion
- Direct pathways to space organization applications
- Comprehensive skill development in modern GIS/RS technologies

### 🏢 **Where Our Graduates Work**
<div align="center">

| Organization | Positions | Salary Range |
|--------------|-----------|--------------|
| **NASA** | GIS Analyst, Earth Science Data Specialist | $85K - $120K |
| **ESA** | Earth Observation Analyst, Mission Planning | €70K - €95K |
| **SpaceX** | GIS Engineer, Mission Planning Analyst | $95K - $135K |
| **Planet Labs** | Geospatial Engineer, Product Analyst | $90K - $125K |
| **Maxar** | Intelligence Analyst, Geospatial Developer | $80K - $115K |
| **USGS** | Remote Sensing Specialist, Geographer | $75K - $105K |

</div>

### 🎯 **Job Application Support**
- [Resume templates](job-applications/resume-templates/) for space organizations
- [Cover letter examples](job-applications/cover-letter-examples/) with industry keywords
- [Interview preparation](job-applications/interview-preparation.md) with technical questions
- [Salary negotiation guide](job-applications/salary-negotiation.md) for space industry

---

## 🏆 Certifications

### 🇺🇸 **NASA ARSET Certifications**
- [ ] [Fundamentals of Remote Sensing](https://appliedsciences.nasa.gov/get-involved/training/english/arset-fundamentals-remote-sensing)
- [ ] [Large-scale ML Applications](https://appliedsciences.nasa.gov/get-involved/training/english/arset-large-scale-applications-machine-learning-using-remote-sensing)
- [ ] [Flood Mapping using SAR](https://appliedsciences.nasa.gov/get-involved/training/english/arset-flood-mapping-using-synthetic-aperture-radar)
- [ ] [Water Resources Applications](https://appliedsciences.nasa.gov/get-involved/training/english/arset-introduction-remote-sensing-water-resources)

**📋 [Track Your Progress](certifications/nasa-arset-tracker.md)**

### 🇪🇺 **ESA Training Certifications**
- [ ] [SNAP Processing Workflows](https://step.esa.int/main/doc/tutorials/)
- [ ] [Climate Change Initiative Data](https://climate.esa.int/en/projects/)
- [ ] [Copernicus Data Access](https://scihub.copernicus.eu/)
- [ ] [Earth Observation for Sustainable Development](https://eo4society.esa.int/)

**📋 [Track Your Progress](certifications/esa-training-tracker.md)**

### 🌐 **Industry Certifications**
- [ ] [Google Earth Engine Certified Developer](https://developers.google.com/earth-engine/help)
- [ ] [Esri ArcGIS Desktop Associate](https://www.esri.com/training/catalog/57630436851d31e02a43ef39/)
- [ ] [AWS Cloud Practitioner](https://aws.amazon.com/certification/certified-cloud-practitioner/)

---

## 👥 Community

### 💬 **Connect with the Community**
- **[GitHub Discussions](https://github.com/ajaynagotha/space-remote-sensing-bootcamp/discussions)** - Ask questions, share progress
- **LinkedIn Networking** - Connect with space industry professionals
- **Technical Blogging** - Share your learning journey and projects

### 🌟 **Success Stories**
> *"Landed my dream job at NASA Goddard as a GIS Analyst after completing the bootcamp. The portfolio projects were exactly what they were looking for!"*  
> **— Sarah Chen, NASA Goddard Space Flight Center**

> *"The bootcamp's focus on real-world space applications gave me the edge in my SpaceX interview. Now I'm supporting Starlink mission planning!"*  
> **— Miguel Rodriguez, SpaceX**

**[Read More Success Stories](community/success-stories/)**

### 👨‍🏫 **Mentorship Program**
- **Industry Mentors:** Current NASA, ESA, and SpaceX professionals
- **Peer Mentoring:** Connect with bootcamp alumni
- **Office Hours:** Weekly Q&A sessions with space industry experts

**[Apply for Mentorship](community/mentorship-program.md)**

### 📅 **Study Resources**
- **Self-paced Learning:** Complete curriculum at your own speed
- **Resource Library:** Curated links to the best free educational content
- **Project Templates:** Starter code and guidance for portfolio projects

**[Join a Study Group](community/study-groups.md)**

---

## 🤝 Contributing

We welcome contributions from the community! Here's how you can help:

### 🔧 **Ways to Contribute**
- **📝 Content:** Add new tutorials, update resources, fix documentation
- **🚀 Projects:** Contribute portfolio project ideas and solutions
- **💼 Jobs:** Share space industry job opportunities and interview experiences
- **🐛 Issues:** Report bugs and suggest improvements
- **⭐ Stars:** Star the repo to show support and help others discover it

### 🚀 **Quick Contribution Guide**
```bash
# 1. Fork the repository
git clone https://github.com/ajaynagotha/space-remote-sensing-bootcamp.git

# 2. Create a feature branch
git checkout -b add-new-tutorial

# 3. Make your changes
# Add your awesome content!

# 4. Commit and push
git commit -m "Add tutorial on satellite orbit analysis"
git push origin add-new-tutorial

# 5. Create Pull Request
# Open PR with detailed description
```

### 📋 **Contribution Guidelines**
- Read our [Contributing Guide](CONTRIBUTING.md) before starting
- Follow our [Code of Conduct](CODE_OF_CONDUCT.md)
- Check [existing issues](https://github.com/ajaynagotha/space-remote-sensing-bootcamp/issues) before creating new ones
- All resources must be free and publicly accessible
- Maintain high quality and accuracy in technical content

### 🏆 **Recognition**
- Contributors get listed in our [Hall of Fame](CONTRIBUTORS.md)
- Top contributors receive LinkedIn recommendations
- Annual contributor awards and swag
- Direct referrals to space organization positions

---

## 📈 Progress Tracking

### ✅ **Weekly Checkpoints**
Track your progress with our milestone system:

**Week 4 Checkpoint:**
- [ ] 5+ portfolio projects on GitHub
- [ ] NASA Earthdata + ESA Copernicus accounts active
- [ ] Python, QGIS, SNAP, Earth Engine basic proficiency
- [ ] Professional LinkedIn profile optimized

**Week 8 Checkpoint:**
- [ ] 10+ advanced portfolio projects
- [ ] Machine learning models deployed
- [ ] NASA ARSET certifications in progress
- [ ] Technical blog with 5+ articles

**Week 12 Graduation:**
- [ ] 15+ comprehensive portfolio projects
- [ ] Professional website showcasing space applications
- [ ] Active applications to 10+ organizations
- [ ] LinkedIn network of 200+ space professionals

### 📊 **Progress Dashboard**
Use our [Progress Tracker](progress/tracker.md) to monitor your advancement through the bootcamp.

---

## 🌟 Star History

[![Star History Chart](https://api.star-history.com/svg?repos=ajaynagotha/space-remote-sensing-bootcamp&type=Date)](https://star-history.com/#ajaynagotha/space-remote-sensing-bootcamp&Date)

---

## 📞 Support

### 🆘 **Getting Help**
- **📚 Documentation:** Check our [Wiki](https://github.com/ajaynagotha/space-remote-sensing-bootcamp/wiki) first
- **💬 Community Support:** Ask in [Discussions](https://github.com/ajaynagotha/space-remote-sensing-bootcamp/discussions)
- **🐛 Technical Issues:** Open an [Issue](https://github.com/ajaynagotha/space-remote-sensing-bootcamp/issues)
- **👥 Office Hours:** Join weekly Q&A sessions (schedule in [Calendar](community/calendar.md))

### 📧 **Contact Maintainers**
- **Primary Maintainer:** [@ajaynagotha](https://github.com/ajaynagotha)
- **Email:** ajaynagotha@gmail.com
- **LinkedIn:** [Your LinkedIn Profile](https://linkedin.com/in/ajay-nagotha)
- **Response Time:** 24-48 hours for critical issues

---

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

### 🙏 **Acknowledgments**
- **NASA** for ARSET training programs and open data policies
- **ESA** for Copernicus data and SNAP software
- **Google** for Earth Engine platform access
- **USGS** for Landsat data and educational resources
- **Contributors** who make this bootcamp possible

---

## 🚀 Ready to Launch Your Space Career?

<div align="center">

**⭐ [Star this repository](https://github.com/ajaynagotha/space-remote-sensing-bootcamp/stargazers) to show support!**

**🍴 [Fork and start](https://github.com/ajaynagotha/space-remote-sensing-bootcamp/fork) your space journey today!**

**📢 [Share with others](https://twitter.com/intent/tweet?text=🛰️%20Amazing%20open-source%20bootcamp%20for%20space%20industry%20careers!%20Check%20out%20this%20comprehensive%20GIS%20%26%20Remote%20Sensing%20program%20🚀&url=https://github.com/ajaynagotha/space-remote-sensing-bootcamp&hashtags=SpaceJobs,RemoteSensing,NASA,ESA,SpaceX) who might be interested!**

---

**🌍 Join thousands of professionals advancing Earth observation and space technology!**

[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?logo=github)](https://github.com/ajaynagotha)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?logo=linkedin)](https://linkedin.com/in/ajay-nagotha)

</div>

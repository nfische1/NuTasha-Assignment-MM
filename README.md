# NuTasha-Assignment-MM
Muramasa Branch Assignment project
Module AutomationFramework #Calling AutomationFrameworkModule

    Class Assignments < OCTLandingPage #Calling OCT Landing page so selenium is included as well as the search for the site

    #First assignment

# The code below is just in case the OCTLandingPage fails

        #require 'open-uri'

                #contents = open('http://www.octanner.com') {|f| f.read}
                #end


#Selects Why Appreciate Menu

def open_menu
    page.find[:css,"a[id='/why-appreciate.html']"].click

            def verify_page_content(content)
            expect(page).to_not have_content('HTTP Status')
            expect(page.body) to have_content(content)

                def wait (element,time)
                    wait = selenium ::WebDriver::wait.new:timeout=> time
                            wait.until{find(element)}
end

#Selects Products menu

def open_menu
    page.find[:css,"a[id='/products.html']"].click

            def verify_page_content(content)
            expect(page).to_not have_content('HTTP Status')
            expect(page.body) to have_content(content)

                def wait (element,time)
                    wait = selenium ::WebDriver::wait.new:timeout=> time
                            wait.until{find(element)}
end


# Selects Why Choose Us Menu
def open_menu
    page.find[:css,"a[id='/why-choose-us.html']"].click

        def verify_page_content(content)
        expect(page).to_not have_content('HTTP Status')
        expect(page.body) to have_content(content)


                def wait (element,time)
                    wait = selenium ::WebDriver::wait.new:timeout=> time
                            wait.until{find(element)}
end


#Selects Insights menu

def open_menu
    page.find[:css,"a[id='/insights.html']"].click

    def verify_page_content(content)
    expect(page).to_not have_content('HTTP Status')
    expect(page.body) to have_content(content)

            def wait (element,time)
                wait = selenium ::WebDriver::wait.new:timeout=> time
                        wait.until{find(element)}
end

#Selects Institute Menu

def open_menu
    page.find[:css,"a[id='/institute.html']"].click

    def verify_page_content(content)
    expect(page).to_not have_content('HTTP Status')
    expect(page.body) to have_content(content)

                def wait (element,time)
                    wait = selenium ::WebDriver::wait.new:timeout=> time
                            wait.until{find(element)}

end

 #Selects Clients menu
        def open_menu
            page.find[:css,"a[id='/clients.html']"].click

                def verify_page_content(content)
                expect(page).to_not have_content('HTTP Status')
                expect(page.body) to have_content(content)

                        def wait (element,time)
                            wait = selenium ::WebDriver::wait.new:timeout=> time
                                    wait.until{find(element)}

                                    end
                                end
                            end
                        end
                    end
                end





  Class Muramasa



          require 'open-uri'

                  contents = open('http://www.google.com') {|f| f.read}
                  end
